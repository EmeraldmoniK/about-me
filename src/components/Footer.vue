<template>
    <div>
        <footer>
        <h2 class="feedback">Связаться со мной</h2>
        <ul class="social">
            <li>
                <a href="">
                    <img src="@/assets/images/Vector.svg" alt="">
                </a>
            </li>
            <li>
                <a href="">
                    <img src="@/assets/images/Vector1.svg" alt="">
                </a>
            </li>
            <li>
                <a href="">
                    <img src="@/assets/images/Vector2.svg" alt="">
                </a>
            </li>
            <li>
                <a href="">
                    <img src="@/assets/images/Vector3.svg" alt="">
                </a>
            </li>
            <li>
                <a href="">
                    <img src="@/assets/images/Vector4.svg" alt="">
                </a>
            </li>
        </ul>
    </footer>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
footer {
    background: #000000;
    padding-top: 46px;
    padding-bottom: 62px;
}
.feedback {
    font-weight: 400;
    font-size: 40px;
    line-height: 49px;
    color: #FFFFFF;
    text-align: center;
}

.social {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 34px;
    gap: 200px;
}

.social img {
    transition: transform 500ms;
}

.social img:hover {
    transform: scale(1.2) rotate(360deg);
}
</style>