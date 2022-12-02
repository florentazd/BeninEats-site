<svelte:head>
    <title>BeninEats | Page d'inscription</title>
</svelte:head>
<section id="signup">
    <div class="cover-container">
        <img src="/images/signup-cover.jpg" alt="">
        <div class="dark-cover">
            <h2 class="text-2xl font-bold">Page d'inscription</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere, eos.</p>
        </div>
    </div>
    <div class="form-container">
        <div class="inner-container">
            <h3 class="text-2xl font-bold">Creer un compte</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing.</p>
            <form action="">
                <div class="name-container">
                    <div class="icon-container">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z" />
                          </svg>
                    </div>
                    <div class="input-container form-control">
                        <label for="" class="label">
                            <span class="label-text">Nom Complet</span>
                        </label>
                        <input type="text" class="input input-bordered" placeholder="Jean Djossou">
                        <label for="" class="label help">
                            <span class="label-text text-xs">Le nom d'utilisateur ne peut être vide</span>
                        </label>
                    </div>
                </div>
                <div class="email-container">
                    <div class="icon-container">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                        </svg>                          
                    </div>
                    <div class="input-container form-control">
                        <label for="" class="label">
                            <span class="label-text">Adresse E-mail</span>
                        </label>
                        <input type="email" class="input input-bordered" placeholder="jean.djosou@benineats.com">
                        <label for="" class="label help">
                            <span class="label-text text-xs">Adresse E-mail invalide</span>
                        </label>
                    </div>
                </div>
                <div class="tel-container">
                    <div class="icon-container">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 15.75V18m-7.5-6.75h.008v.008H8.25v-.008zm0 2.25h.008v.008H8.25V13.5zm0 2.25h.008v.008H8.25v-.008zm0 2.25h.008v.008H8.25V18zm2.498-6.75h.007v.008h-.007v-.008zm0 2.25h.007v.008h-.007V13.5zm0 2.25h.007v.008h-.007v-.008zm0 2.25h.007v.008h-.007V18zm2.504-6.75h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V13.5zm0 2.25h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V18zm2.498-6.75h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V13.5zM8.25 6h7.5v2.25h-7.5V6zM12 2.25c-1.892 0-3.758.11-5.593.322C5.307 2.7 4.5 3.65 4.5 4.757V19.5a2.25 2.25 0 002.25 2.25h10.5a2.25 2.25 0 002.25-2.25V4.757c0-1.108-.806-2.057-1.907-2.185A48.507 48.507 0 0012 2.25z" />
                          </svg>                          
                    </div>
                    <div class="input-container form-control">
                        <label for="" class="label">
                            <span class="label-text">Numéro de téléphone</span>
                        </label>
                        <input type="text" class="input input-bordered" placeholder="Jean Djossou">
                        <label for="" class="label help">
                            <span class="label-text text-xs">Numéro de téléphone invalide</span>
                        </label>
                    </div>
                </div>
                <div class="password-container">
                    <div class="icon-container">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z" />
                          </svg>                          
                    </div>
                    <div class="input-container form-control">
                        <label for="" class="label">
                            <span class="label-text">Mot de passe</span>
                        </label>
                        <input type="password" class="input input-bordered" placeholder="******">
                        <label for="" class="label help">
                            <span class="label-text text-xs">Votre mot de passe est faible.</span>
                        </label>
                    </div>
                </div>
                <div class="submit-container">
                    <button type="submit" class="btn btn-link">Créer mon compte</button>
                </div>
                <div class="alt-container">
                    <p>Vous avez déjà un compte ?<button class="btn btn-link">Vous connecter</button></p>
                </div>
            </form>
        </div>
    </div>
    <!-- TODO: Inscription par google ou twitter prochainement -->
</section>

<style>
    section{
        height: 100vh;
    }    

    .inner-container h3{
        color: #182135;
    }
    .form-container{
        background-color: #fff;
    }
    .inner-container{
        display: flex;
        row-gap: 15px;
        flex-direction: column;
    }

    .help{
        display: none;
    }
    form{
        display: flex;
        flex-direction: column;
        row-gap: 30px;
    }
    form > div{
        display: grid;
    }
    form input{
        border: 0px;
        border-bottom: 1px solid #f6e58d;
        border-radius: 0px;
        outline: none !important;
    }

    .submit-container{
            /*  */
    }
    .submit-container button{
        color: #182135;
        text-decoration: none;
        border-radius: 7px;
        width: 100%;
        background-color: #f6e58d;
        text-transform: none;
    }
    .alt-container{
        display: flex;
        justify-content: center;
    }
    .alt-container button{
        text-transform: none;
        color: #f6e58d;
    }

        /* .icon-container{
            background-color: #f6e58d;
            height: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 10px;
        } */

    @media screen and (max-width: 960px){
        /* cover container */
        .cover-container{
            display: none
        }

        /* form-container */
        .form-container{
            height: fit-content;
        }

        /* .form-container{
            display: flex;
            justify-content: center;
            align-items: center;
        } */
        
        .inner-container{
            padding: 60px 15px;
        }

        .icon-container{
        display: none;
    }
    }

    @media screen and (min-width: 960px){
        section{
            display: grid;
            grid-template-columns: 40% 60%;
        }

        /* cover container */
        .cover-container{
            background-color: darkblue;
            height: 100vh;
            position: relative;
        }
        .cover-container img{
            height: 100%;
            width: 100%;
            object-fit: cover;
        }
        .dark-cover{
            position: absolute;
            top: 0px;
            left: 0px;
            background-color: #00000080;
            height: 100%;
            width: 100%;
            color: #F2F2F2;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 0px 20px;
        }

        /* form-container */
        .form-container{
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .inner-container{
            width: 550px;
            padding: 40px;
        }
        
        form > div:not(.submit-container, .alt-container){
            grid-template-columns: 60px 1fr;
        }
        form > div{
            column-gap: 20px;
            align-items: center;
        }
        .icon-container{
            background-color: #f6e58d;
            height: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 10px;
        }
    }
</style>