<script>
    import Dog from "$lib/Dog.svelte";
</script>
<div class="interests">
    <p style="color:blue; font-weight: bold;">My interests!</p>
    <div class = "cats" style="font-weight: bold;">
            I love animals! My family even have 5 cats: Lisa, Sonya, Lexus, Vesta and Tucha 😍
            Look at them!
        <div class="pictures">
                <img src="/static/source/lisa.jpg" style="width: 18%; border: 4px solid #87CEEB;">
                <img src="/static/source/sonya.jpg" style="width: 18%; border: 4px solid #87CEEB;">
                <img src="/static/source/lexus.jpg" style="width: 18%; border: 4px solid #87CEEB;">
                <img src="/static/source/vesta.jpg" style="width: 18%; border: 4px solid #87CEEB;">
                <img src="/static/source/tucha.jpg" style="width: 18%; border: 4px solid #87CEEB;">
        </div>
            I used to have a dog but... I don't have any now, so I like to look at virtual dogs 😌
            <Dog />
    </div>
</div>

<style>
    .interests{
    width: 97%;
    font-size: 26px;
    line-height: 20px;
    font-family: "My Custom Font";
}

.cats{
    font-size: 20px;
    display: flexbox;
}

.pictures{
    text-align: center;
    display: flexbox;
    padding: 25px;
}  
</style>