<template>
    <div class="container">
        <div class="card">
            <div class="qr">
            <img src="../assets/image-qr-code.png" alt="">
            </div>
            <div class="description">
                <div class="bold">
                    Improve your front-end skills by building projects
                </div>
                <div class="paragraph">
                    Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
                </div>
            </div>
        </div>
        

    </div>
</template>


<style scoped>
    .container{
        border-radius: 18px;
        padding: 18px 18px 36px 18px;
        max-width: 340px;
        margin: 0 auto;
        background-color: white;
        text-align: center;
    }
    img{
        width: 100%;
        vertical-align: middle;
        border-radius: 9px;
        margin-bottom: 24px;
    }
    .bold{
        font-size: 24px;
        font-weight: 700;
        color: hsl(218, 44%, 22%);
        margin-bottom: 24px;
    }
    .paragraph{
        font-size: 15px;
        font-weight: 400;
        color: hsl(220, 15%, 55%);
    }
    .bold, .paragraph{
        padding-left: 12px;
        padding-right: 12px;
    }

    @media only screen and (max-width: 455px){
        .container{
            margin-left: 20px;
            margin-right: 20px;
        }
    }
</style>