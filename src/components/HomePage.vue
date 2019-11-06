<template>
    <div class="container">
        <div class="header">
            <div class="side-header">
                <div class="phone-header">
                    <img alt="Vue logo" src="../assets/images/SB-Website--Ar-2-Slicing_46.png">
                    +965 9410 4734  +965 9228 7577
                </div>
                <div class="phone-header">
                    <img alt="Vue logo" src="../assets/images/SB-Website--Ar-2-Slicing_60.png">
                    +965 2209 2288
                </div>
            </div>
            <div class="logo">
                <img alt="Vue logo" src="../assets/images/SB-Website--Ar-2-Slicing_03.png">
            </div>
        </div>

        <div>
            <b-navbar class="navbar" toggleable="lg">
                <b-navbar-nav class="mr-auto">
                    <b-nav-item href="">EN</b-nav-item>
                    <b-nav-item href="">تواصل معنا</b-nav-item>
                    <b-nav-item href="">عملائنا</b-nav-item>
                    <b-nav-item-dropdown text="البروفايل" left>
                        <b-dropdown-item href="#">النسخة العربية</b-dropdown-item>
                        <b-dropdown-item href="#">النسخة الإنجليزية</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item href="">الصفحة الرئيسية</b-nav-item>
                </b-navbar-nav>
                <b-navbar-brand>الوسيط البسيط</b-navbar-brand>
            </b-navbar>
        </div>

        <div class="page">
            <div class="content" style="display: flex;">
                <div style="font-size: 340%;text-align: right;">
                    خدمة الطلب عن طريق 
                    <strong>الموقع الإلكتروني</strong>
                     الخاص بك
                </div>
                <div>
                    <img width="600px" alt="Vue logo" src="../assets/images/SB-Website--Ar-2-Slicing_09.png">
                </div>
            </div>
            <div class="content">
                <div >
                    <img width="750px" alt="Vue logo" src="../assets/images/SB-Website--Ar-2-Slicing_16.png">
                </div>
            </div>
            <div class="content" style="display: flex; margin-top:50px;">
                <div>
                    <img width="700px" height="120px" alt="Vue logo" src="../assets/images/SB-Website--Ar-2-Slicing_20.png">
                </div>
                <div>
                    <img width="250px" height="120px" alt="Vue logo" src="../assets/images/SB-Website--Ar-2-Slicing_22.png">
                </div>
            </div>
        </div>

        <div class="footer">

        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.container{
    margin: 0 auto;
    max-width: 1040px;
    min-width: 763;
    width: 100%;
}
.header{
    display: flex;
    place-content: space-between;
}
.side-header{
    display: flex;
}
.phone-header{
    margin-top: 60px;
    margin-left:20px;
}
.navbar{
    background:#383f59;
    width: 100%;
    height: 40px;
}
.navbar .navbar-brand,
.navbar .navbar-nav .nav-item .nav-link,
.navbar .navbar-nav .nav-item .nav-link span{
    color: white;
}
.content{
    width: 100%;
    align-items: center;
}
</style>