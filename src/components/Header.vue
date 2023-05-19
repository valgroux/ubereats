<template>
    <nav class="navigation">
        <div class="nav_left">
            <img src="../assets/img/burger.svg">
            <img src="../assets/img/logo.svg">
        </div>
        <div class="nav_right">
            <div class="nav_right-icon">
                <img src="../assets/img/panier.svg" alt="Icone du panier">
                <p>Panier</p>
            </div>
            <div class="nav_right-icon">
                <img src="../assets/img/connexion.svg" alt="Icone de connexion">
                <p>Connexion</p>
            </div>
            <div class="nav_right-icon">
                <p>Inscription</p>
            </div>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .navigation{
        display: flex;
        justify-content: space-around;
        margin-bottom: 24px;
            .nav_left{
            display: flex;
            gap: 24px;
            width: 50%;
            img {
                width: 20%;
            }
                img:first-child{
                    width: 3%;
                    flex-grow: 0;
                }
            }
            .nav_right{
            display: flex;
            width: 50%;
            justify-content: flex-end;
            gap: 24px;
                .nav_right-icon{
                    display: flex;
                    align-items: center;
                    background-color: #000;
                    padding: 10px 12px;
                    gap:8px;
                    border-radius:25px;
                    color:#fff;
                    cursor: pointer;
                    transition: 0.3s;
                    &:hover{
                        background-color: #3c3c3c;
                    }
                }
                .nav_right-icon:nth-child(2),
                .nav_right-icon:nth-child(3){
                    background-color:#EEEEEE;
                    color:#000;
                    &:hover{
                        background-color:#e8e8e8;
                    }
                }
            }
    }


</style>