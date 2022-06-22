<div class="contact" id="contact">
    <h1>Contact Me</h1>

    <div class="contact-links">
        <a href="https://github.com/Vldmr314" target="_blank"><img src="/img/git_icon.png"
                                                                   alt="github"/></a>
        <a href="https://vk.com/vladimir31415" target="_blank"><img src="/img/vk_icon.png" alt="vk"/></a>
        <a href="https://www.instagram.com/_.mr_volodya._" target="_blank"><img src="/img/inst_icon.png"
                                                                                alt="instagram"/></a>
        <a href="https://t.me/Vldmr11" target="_blank"><img src="/img/tg_icon.png" alt="telegram"/></a>
    </div>
</div>

<style>
    .contact {
        margin: 0;
        position: absolute;
        top: 300vh;
        height: 100vh;
        width: 100vw;
        background: url("/img/contact_back.jpeg") no-repeat;
        background-size: cover;
        color: white;
    }

    h1 {
        font-family: "Xirod", sans-serif;
        letter-spacing: 3px;
        font-size: 46px;
        display: flex;
        justify-content: center;
        margin-top: 5vh;
    }

    .contact-links {
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;
        align-items: center;
        margin: 0 auto;
        max-width: 640px;
        padding: 16px 8px 0 8px;
    }

    a {
        margin-top: 10%;
    }

    img {
        transition: 0.2s;
        width: 48px;
        will-change: filter;
    }

    img:hover {
        transform: scale(1.2);
    }
</style>