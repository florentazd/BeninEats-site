<div class="w-full h-screen flex flex-col gap-y-4">
    <!-- Liste des partenaires importants -->
    <div class="w-full h-fit flex flex-col gap-y-4">
        <div id="resto-header-container" class="h-10 flex justify-between items-center">
            <h3 id="header-title" class="text-xl text-[#182135] font-semibold">Nos partenaires</h3>
            <span id="see-more-resto" class="text-sm">Tout voir ></span>
        </div>
        <div id="partner-container" class="h-fit w-fit sm:w-full max-w-full grid sm:grid-cols-3 gap-4 overflow-x-auto">
            <div class="bg-slate-500 h-28 w-72 sm:w-full"></div>
            <div class="bg-slate-100 h-28 w-72 sm:w-full"></div>
            <div class="bg-slate-400 h-28 w-72 sm:w-full"></div>
            <div class="bg-slate-200 h-28 w-72 sm:w-full"></div>
            <div class="bg-slate-600 h-28 w-72 sm:w-full"></div>
            <div class="bg-slate-500 h-28 w-72 sm:w-full"></div>
        </div>
    </div>

    <!-- Une catégorie -->
    <div class="w-full h-fit flex flex-col gap-y-4">
        <div id="resto-header-container" class="h-10 flex justify-between items-center">
            <h3 id="header-title" class="text-xl text-[#182135] font-semibold">Pizzas</h3>
            <span id="see-more-resto" class="text-sm">Tout voir ></span>
        </div>
        <div id="first-category-container" class="h-fit w-full sm:w-full max-w-full grid sm:grid-cols-3 gap-y-8 sm:gap-4">
            <div class="bg-slate-500 h-60 sm:h-52 w-full flex "></div>
            <div class="bg-slate-100 h-60 sm:h-52 w-full"></div>
            <div class="bg-slate-400 h-60 sm:h-52 w-full"></div>
            <div class="bg-slate-500 h-60 sm:h-52 w-full"></div>
        </div>
    </div>
    <!-- Deuxie catégorie -->
    
    <div class="w-full h-fit flex flex-col gap-y-4">
        <div id="resto-header-container" class="h-10 flex justify-between items-center">
            <h3 id="header-title" class="text-xl text-[#182135] font-semibold">Burgers</h3>
            <span id="see-more-resto" class="text-sm">Tout voir ></span>
        </div>
        <div id="first-category-container" class="h-fit w-full sm:w-full max-w-full grid sm:grid-cols-3 gap-y-8 sm:gap-4">
            <div class="bg-slate-500 h-60 sm:h-52 w-full flex "></div>
            <div class="bg-slate-100 h-60 sm:h-52 w-full"></div>
            <div class="bg-slate-400 h-60 sm:h-52 w-full"></div>
            <div class="bg-slate-500 h-60 sm:h-52 w-full mb-5"></div>
        </div>
    </div>
</div>
<style>
        @media screen and (max-width: 960px) {
            #partner-container{
                grid-template-columns: repeat(3, 288px);
            }

            #first-category-container{
                grid-template-columns: 1fr;
            }
        }
</style>