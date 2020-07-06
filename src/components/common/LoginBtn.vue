<template>
    <div class="btnparent">
        <div class="loginbtn">{{btntext}}</div>
    </div>
 
</template>

<script>
export default {
    props: ['btntext']
};
</script>

<style>
.btnparent {
    margin: 4.1667vw 2.7778vw;
}
.loginbtn {
    height: 12.5vw;
    background-color: #ff9db5;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 4.444vw;
    border-radius: 6.25vw;
}
</style>
