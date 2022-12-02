<svelte:head>
    <title>BeninEats | Page d'inscription</title>
</svelte:head>
<section id="signup">
    <div class="cover-container">
        <img src="/images/recup-cover.jpg" alt="">
        <div class="dark-cover">
            <h2 class="text-2xl font-bold">Page de réinitialisation</h2>
            <p>Vite, Vite nous vous attendons.</p>
        </div>
    </div>
    <div class="form-container">
        <div class="inner-container">
            <h3 class="text-2xl font-bold">Mot de passe oublié ?</h3>
            <p>Entrer votre adresse e-mail pour réinitialiser votre mot de passe.</p>
            <form action="">
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
                <div class="submit-container">
                    <button type="submit" class="btn btn-link">Réinitialiser mon mot de passe</button>
                </div>
                <div class="alt-container">
                    <p>Vous avez vos identifiants ?<button class="btn btn-link"><a href="/connexion">Connectez-vous</a></button></p>
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
        background-color: transparent;
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
        h3, p, label span{
            color: #F2F2F2 !important;
        }

        input{
            color: #fff;
        }
        
        /* cover container */
        .cover-container{
            display: none
        }

        /* form-container */
        .form-container{
            height: fit-content;
            background: url("/images/login-cover.jpg") center/cover;

        }

        /* .form-container{
            display: flex;
            justify-content: center;
            align-items: center;
        } */
        
        .inner-container{
            padding: 30px 15px;
            height: 100vh;
            background-color: #00000080;
            display: flex;
            justify-content: center;
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