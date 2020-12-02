<template>
    <footer>
        <div class="footer-content">
            <p>
                Analytics Dashboard
            </p>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer",
    data(){
        return{

        }
    }
}
</script>

<style>
    footer{
        width: 100%;
        background-color: #fff;
        text-align: center;
    }

    footer .footer-content{
        margin-left: 337px;
    }

    @media only screen and (max-width: 768px){
        footer .footer-content{
            margin-left: 0;
        }
    }
</style>
