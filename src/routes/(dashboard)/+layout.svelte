<script>
	import { page } from "$app/stores";
  let product = {
    number:0
  }
</script>

<svelte:head>
    <title>Dashboard | Username Title</title>
</svelte:head>
<section id="dashboard">
    <div class="drawer drawer-mobile">
        <input id="menu-drawer" type="checkbox" class="drawer-toggle" />
        <div class="drawer-content flex flex-col items-center justify-center">
        <div class="content-container bg-[#fff] w-full h-full">
          <!-- Page content here -->
          <div class="navbar bg-[#ffffff] fixed sm:relative z-10 shadow-lg  sm:shadow-none justify-between">
            <div class="nav-content-left hidden sm:flex pl-3">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2f3640" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
              </svg>
              <button class="btn btn-link text-[#A4A4A4] normal-case no-underline">Entrer votre addresse</button>              
            </div>
            <div class="flex-none lg:hidden">
                <label for="menu-drawer" class="btn btn-square btn-ghost">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5M12 17.25h8.25" />
                      </svg>
                </label>
              </div> 
            <div class="flex-none">
              <div class="dropdown dropdown-end">
                <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
                <!-- svelte-ignore a11y-label-has-associated-control -->
                <label tabindex="0" class="btn btn-ghost btn-circle">
                  <div class="indicator">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" /></svg>
                    <span class="badge badge-sm indicator-item">8</span>
                  </div>
                </label>
                <div tabindex="0" class="mt-3 card card-compact dropdown-content w-52 bg-base-100 shadow">
                  <div class="card-body">
                    <span class="font-bold text-lg">8 Items</span>
                    <span class="text-info">Subtotal: $999</span>
                    <div class="card-actions">
                      <button class="btn btn-primary btn-block">View cart</button>
                    </div>
                  </div>
                </div>
              </div>
              <div class="dropdown dropdown-end">
                <label tabindex="0" class="btn btn-ghost btn-circle avatar">
                  <div class="w-10 rounded-full">
                    <img src="https://placeimg.com/80/80/people" />
                  </div>
                </label>
                <ul tabindex="0" class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
                  <li>
                    <a class="justify-between">
                      Profile
                      <span class="badge">New</span>
                    </a>
                  </li>
                  <li><a>Settings</a></li>
                  <li><a>Logout</a></li>
                </ul>
              </div>
            </div>
          </div>
          <div class="page-content text-center sm:text-left p-5 h-fit relative top-14 sm:top-0 ">
              <slot/>
          </div>
        </div>
        </div> 
        <div class="drawer-side">
          <label for="menu-drawer" class="drawer-overlay"></label>
          <div class="sidebar bg-[#F7F7F7] w-80 text-base-content">
            <div class="header-container bg-[#2f3640] h-[67px]">
                <img height="60" width="60" src="/images/dash-logo.png" alt="">
                <h3 class="text-white text-3xl font-semibold">BeninEats</h3>
            </div>
            <ul class="menu p-4">
                <li class:active={$page.url.pathname == "/home"} >
                    <!-- svelte-ignore a11y-missing-attribute -->
                    <a href="/home">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" /></svg>
                    <span>Acceuil</span>
                    </a>
                </li>
                <li class:active={$page.url.pathname == "/decouverte"}>
                      <!-- svelte-ignore a11y-missing-attribute -->
                    <a href="/decouverte">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 15.75l-2.489-2.489m0 0a3.375 3.375 0 10-4.773-4.773 3.375 3.375 0 004.774 4.774zM21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                      <span>Découverte</span>
                    </a>
                </li>
                <li class:active={$page.url.pathname == "/favoris"}>
                      <!-- svelte-ignore a11y-missing-attribute -->
                    <a href="/favoris">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
                        </svg>
                      <span>Vos Favoris</span>
                    </a>
                </li>
                <li class:active={$page.url.pathname == "/commandes"}>
                      <!-- svelte-ignore a11y-missing-attribute -->
                    <a href="/commandes">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
                        </svg>
                      <span>Mes Commandes</span>
                    </a>
                </li>
                <li class:active={$page.url.pathname == "/messages"}>
                      <!-- svelte-ignore a11y-missing-attribute -->
                    <a href="/messages">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.76c0 1.6 1.123 2.994 2.707 3.227 1.068.157 2.148.279 3.238.364.466.037.893.281 1.153.671L12 21l2.652-3.978c.26-.39.687-.634 1.153-.67 1.09-.086 2.17-.208 3.238-.365 1.584-.233 2.707-1.626 2.707-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0012 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018z" />
                        </svg>
                      <span>Messages</span>
                    </a>
                </li>
                <li class:active={$page.url.pathname == "/parametres"}>
                      <!-- svelte-ignore a11y-missing-attribute -->
                    <a href="/parametres">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M10.343 3.94c.09-.542.56-.94 1.11-.94h1.093c.55 0 1.02.398 1.11.94l.149.894c.07.424.384.764.78.93.398.164.855.142 1.205-.108l.737-.527a1.125 1.125 0 011.45.12l.773.774c.39.389.44 1.002.12 1.45l-.527.737c-.25.35-.272.806-.107 1.204.165.397.505.71.93.78l.893.15c.543.09.94.56.94 1.109v1.094c0 .55-.397 1.02-.94 1.11l-.893.149c-.425.07-.765.383-.93.78-.165.398-.143.854.107 1.204l.527.738c.32.447.269 1.06-.12 1.45l-.774.773a1.125 1.125 0 01-1.449.12l-.738-.527c-.35-.25-.806-.272-1.203-.107-.397.165-.71.505-.781.929l-.149.894c-.09.542-.56.94-1.11.94h-1.094c-.55 0-1.019-.398-1.11-.94l-.148-.894c-.071-.424-.384-.764-.781-.93-.398-.164-.854-.142-1.204.108l-.738.527c-.447.32-1.06.269-1.45-.12l-.773-.774a1.125 1.125 0 01-.12-1.45l.527-.737c.25-.35.273-.806.108-1.204-.165-.397-.505-.71-.93-.78l-.894-.15c-.542-.09-.94-.56-.94-1.109v-1.094c0-.55.398-1.02.94-1.11l.894-.149c.424-.07.765-.383.93-.78.165-.398.143-.854-.107-1.204l-.527-.738a1.125 1.125 0 01.12-1.45l.773-.773a1.125 1.125 0 011.45-.12l.737.527c.35.25.807.272 1.204.107.397-.165.71-.505.78-.929l.15-.894z" />
                          <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                      <span>Paramètres</span>
                    </a>
                </li>
            </ul>
          </div>
        </div>
      </div>
</section>

<!-- Affichage de la vue des repas -->
<input type="checkbox" id="product-view" class="modal-toggle" />
<div for="product-view" class="z-30 modal cursor-pointer modal-bottom sm:modal-middle ">
  <div id="rbix"  class="p-0 cursor-default modal-box h-[60vh] lg:h-[600px] grid grid-rows-[100px,1fr,80px] sm:grid-rows-[208px,1fr,80px]">

    <div class="hidden sm:block">
      <img src="/images/attieke.jpg" class="sm:h-full sm:w-full object-cover" alt="">
      <button class="h-[60px] w-[60px] absolute top-2 right-2 bg-white rounded-xl flex justify-center items-center">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
        </svg>
      </button>
      <button class="h-[60px] w-[60px] absolute top-2 left-2 bg-[#c03a2bb8] text-white rounded-xl">
        <label for="product-view" class="cursor-pointer h-full w-full  flex justify-center items-center">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
          </svg>
        </label>
      </button>
    </div>
    <div class="flex sm:hidden">
      <!--  -->
    </div>

    <!-- Product details -->
    <div id="product-details" class="font-sans sm:font-['Poppins'] bg-[#fff] hidden sm:flex sm:flex-col px-8 py-6 gap-y-2 pb-2">
      <div class="flex justify-between">
        <h3 class="font-bold text-[24px]">Attieke au Poisson</h3>
        <div class="text-xs flex items-center justify-center gap-1">
          <span class="text-sm relative top-[2px]">4.5</span> 
          <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
              <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
          </svg>
        </div>
      </div>
      <!--  -->
      <p class="text-sm text-[#A4A4A4]">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Odio, accusamus.</p>
      <!--  -->
      <div class="flex justify-between ">
        <div class="flex flex-row gap-x-1 items-center">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#A4A4A4" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>                                                           
          <span class="text-sm text-[#A4A4A4]">30min</span>
        </div>
        <div class="flex flex-row gap-x-1 items-center">
          <span class="text-md badge text-[#fff]">2000F</span>
        </div>
      </div>
      <div class="h-full w-full  rounded-lg mt-3">
        <textarea class="p-2 outline-none rounded-lg h-full w-full bg-[#F5F5F5] resize-none" placeholder="Ajouter un commentaire à la commande"/>
      </div>
    </div>
    <div class="flex sm:hidden">
      <!--  -->
    </div>
    <!--  -->
    <div id="actions" class="grid grid-cols-[140px,1fr] gap-x-2 items-center px-4">
      <div class="bg-[#F7F7F7] h-16 rounded-xl grid grid-cols-[32px,1fr,32px] px-2 items-center justify-between">
        <button on:click={() => {
          if(product.number - 1 >= 0)
            product.number-=1
        }}>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M18 12H6" />
          </svg>
        </button>
        <span class="text-lg font-bold flex items-center justify-center">{product.number}</span>
        <button on:click={() => (product.number+=1)}>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
          </svg>
        </button>
      </div>
      <button class="btn h-16 normal-case bg-[#2f3640]">Ajouter au panier (0F)</button>
    </div>
  </div>
</div>
<!-- Fin d'affichage -->

<style>
  @media screen and (min-width: 960px){
    #rbix{
      width: 400px !important;
    }
  }
    .header-container{
        display: flex;
        align-items: center;
        padding: 0px 20px;
        column-gap: 10px;
    }

    li{
        height: 52px;
        border-radius: 10px;
    }

    li.active{
        background-color: #2f3640 ;
        color: #F7F7F7;
    }
    li a{
        height: 100%;
    }

    a:focus, a:active{
        background-color: #1F29371A !important;
        color: #2f3640;
    }
</style>