<script>
    import { base } from '$app/paths';
</script>

<style>
    .portfolio {
        width: 97%;
        padding: 7px;
        font-size: 26px;
        line-height: 20px;
        font-family: "My Custom Font";
    }
    .profile {
        display: flex;
        flex-direction: row;
    }
    
    .portfolio .q { font-weight: bold; }
    
    </style>
    <div class="profile">
        <div class="avatar">
            <img style="
            border: 9px solid #87CEEB;
            width: 80%;
            top: 135px;
            left: 150px;"
            src="{base}/source/xielan.jpg">
        </div>
        <div class="portfolio" style="
            border: 4px solid #87CEEB;
            background-color: #ffffff80;">
            <div class="about">
                <p><span class="q"> Name: </span> Lera</p>
                <p><span class="q"> Age: </span> 21</p>
                <p><span class="q"> Current location: </span> Innopolis</p>
                <p><span class="q"> Hobbies: </span> drawing, online gaming</p>
                <p><span class="q"> Contact me via:<a href="https://www.linkedin.com/in/lera-istomina-2b2820245/">LinkedIn<img src="{base}/source/linkedin-icon.png" style="width: 1em"></a>
                                                        <a href="https://t.me/geralizz">Telegram<img src="{base}/source/telegram-logo.png" style="width: 1em"></a></span></p>
            </div>
        </div>
    </div>
    
