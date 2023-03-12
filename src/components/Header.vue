<template>
    <div>
        <header>
        <nav>
            <div class="container header-nav">
                <a href="#" class="logo">PROWEB</a>
                <ul>
                    <li v-for="(link,i) in links" :key="i"> 
                        <a href="#">
                            {{ link }}
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
        <div class="header-content">
            <h1>Добро пожаловать на мой сайт</h1>
            <a href="tel:+998907777777" class="call">Позвонить</a>
        </div>
    </header>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                links: ['Обо мне','Мои работы','Контакты']
            }
        }
    }
</script>

<style scoped>
    nav {
    background: #000000;
    padding: 14px 0;
}
.logo {
    color: #FFFFFF;
    font-size: 40px;
    line-height: 48px;
    font-weight: 700;
}
.header-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
header ul {
    display: flex;
    gap: 75px;
}

header ul a {
    color: #FFFFFF;
    font-size: 25px;
    line-height: 30px;
    transition: color 500ms;
}
header ul a:hover {
    color: orange;
}
.header-content {
    height: 850px;
    background: url(@/assets/images/bg.jpg) no-repeat center /cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 150px;
}
.header-content h1 {
    font-size: 40px;
    line-height: 48px;
    color: #000000;
}

.call {
    background: #FFFFFF;
    border-radius: 10px;
    font-weight: 700;
    font-size: 35px;
    line-height: 42px;
    color: #000000;
    padding: 10px 23px;
    transition: color 300ms, background 300ms;
}
.call:hover {
    background: black;
    color: white;
}
</style>