<script>

</script>


    <div class="mx-auto">
        <header class="header">
            <div class="imgName">
                <div>
                    <img class="imgName_CustomImage" src="images/imgPerfil.JPG" alt="Manuel Quiroga">
                </div>
                <div>
                    <span>Manuel Quiroga</span>
                </div>
            </div>
            <div class="nav_links">
                <ul>
                    <li>
                        <a href="">About</a>
                        <a href="">Courses</a>
                        <a href="">Projects</a>
                        <a href="">Contact</a>
                    </li>
                </ul>
            </div>
            <div class="social-icons">
                <div class="custom_Icon"><i class="fa-brands fa-linkedin" style="color: white;"></i></div>
                <div class="custom_Icon"><i class="fa-brands fa-square-github" style="color: white;"></i></div>
                <div class="custom_Icon"><i class="fa-regular fa-sun" style="color: white;"></i></div>
                <div class="custom_Icon"><i class="fa-solid fa-moon" style="color: white;"></i></div>
            </div>
        </header>
    </div>

<style>
    ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    li{
        text-decoration: none;
    }
    a{
        text-decoration: none;
        color: white;
        margin-right: 15px;
        font-size: 20px;
        font-weight: 600;
    }
    .mx-auto{
        margin-left: auto;
        margin-right: auto;
        align-items: center;
        background-color: #091A28;
    }
    .header{
        display: flex;
        justify-content: space-between;
        margin-left: 10px;
        margin-right: 20px;
        padding-top: 1rem;
        padding-bottom: 1rem;
        align-items: center;
    }
    /* Sección Imagen y nombre */
    .imgName{
        display: flex;
        gap: 16px;
        align-items: center;
        color: white;
    }
    .imgName_CustomImage{
        border-radius: 50%;
        width: 50px;
        height: 50px;
        object-fit: cover;
    }
    .social-icons{
        display: flex;
        justify-content: end;
        gap: 15px;
    }
    .custom_Icon{
        font-size: 1.5rem;
    }
</style>