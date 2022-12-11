<div class="w-full h-screen flex flex-col gap-y-4">
    <!-- Liste des partenaires importants -->
    <div class="w-full h-fit flex flex-col gap-y-4">
        <div id="resto-header-container" class="h-10 flex justify-between items-center">
            <h3 id="header-title" class="text-xl text-[#182135] font-semibold">Nos partenaires</h3>
            <span id="see-more-resto" class="text-sm">Tout voir ></span>
        </div>
        <div id="partner-container" class="h-fit w-fit sm:w-full max-w-full grid sm:grid-cols-3 gap-4 overflow-x-auto">
            {#each Array(6) as _}
            <div class="bg-[#F7F7F7] rounded partner h-28 w-72 sm:w-full flex cursor-pointer indicator">
                <div class="rounded w-24 flex items-center justify-center">
                    <img src="/images/restaurant.png" alt="" class="w-[60%] h-[50%] object-cover">
                </div>
                <div class="right-container grid grid-rows-3">
                    <div class="partner-name-container flex items-end">
                        <h3 class="font-semibold text-[#182135]">Cornelia Resto</h3>
                    </div>
                    <!--  -->
                    <div class="partner-details-container flex items-center justify-between pr-3">
                        <div class="flex flex-row gap-x-1 items-center">
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-xs">4.5</span>
                        </div>
                        <div class="flex flex-row gap-x-1 items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>                                                           
                            <span class="text-xs">8h-19h</span>
                        </div>
                        <div class="flex flex-row gap-x-1 items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18.75a60.07 60.07 0 0115.797 2.101c.727.198 1.453-.342 1.453-1.096V18.75M3.75 4.5v.75A.75.75 0 013 6h-.75m0 0v-.375c0-.621.504-1.125 1.125-1.125H20.25M2.25 6v9m18-10.5v.75c0 .414.336.75.75.75h.75m-1.5-1.5h.375c.621 0 1.125.504 1.125 1.125v9.75c0 .621-.504 1.125-1.125 1.125h-.375m1.5-1.5H21a.75.75 0 00-.75.75v.75m0 0H3.75m0 0h-.375a1.125 1.125 0 01-1.125-1.125V15m1.5 1.5v-.75A.75.75 0 003 15h-.75M15 10.5a3 3 0 11-6 0 3 3 0 016 0zm3 0h.008v.008H18V10.5zm-12 0h.008v.008H6V10.5z" />
                              </svg>                              
                            <span class="text-xs">$$$</span>
                        </div>
                    </div>
                    <!--  -->
                    <div class="delivery-details-container flex items-center justify-between">
                        <div class="flex gap-x-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2f3640" class="w-4 h-4">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                              </svg>
                              <span class="text-xs">2.5 Km</span>
                        </div>
                    </div>
                </div>
            </div>
            {/each}
        </div>
    </div>

    <!-- Une catégorie -->
    <div class="w-full h-fit flex flex-col gap-y-4">
        <div id="resto-header-container" class="h-10 flex justify-between items-center">
            <h3 id="header-title" class="text-xl text-[#182135] font-semibold flex items-center gap-1">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                 <path stroke-linecap="round" stroke-linejoin="round" d="M9.568 3H5.25A2.25 2.25 0 003 5.25v4.318c0 .597.237 1.17.659 1.591l9.581 9.581c.699.699 1.78.872 2.607.33a18.095 18.095 0 005.223-5.223c.542-.827.369-1.908-.33-2.607L11.16 3.66A2.25 2.25 0 009.568 3z" />
                 <path stroke-linecap="round" stroke-linejoin="round" d="M6 6h.008v.008H6V6z" />
                </svg>
                <span>Fast-Food</span>
            </h3>
            <span id="see-more-resto" class="text-sm">Tout voir ></span>
        </div>
        <div id="first-category-container" class="h-fit w-full sm:w-full max-w-full grid sm:grid-cols-3 gap-y-8 sm:gap-4">
            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/pizza_1.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Burger Classique</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>Resto du coeur</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge items-center text-[#fff] gap-1">
                            2.500F
                        </p>
                    </div>
                </div>
            </div>
            <!--  -->
            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/spaghetti.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Spaghetti Bolognaise</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>Festo</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge  items-center text-[#fff] gap-1">
                            4.000F
                        </p>
                    </div>
                </div>
            </div>
            <!--  -->
            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/spaghetti_2.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Spaghetti Bolognaise</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>Festo</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge  items-center text-[#fff] gap-1">
                            4.000F
                        </p>
                    </div>
                </div>
            </div>
            <!--  -->
            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/riz_blanc.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Riz Blanc Simple</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>Cornelia</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge  items-center text-[#fff] gap-1">
                            4.000F
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Deuxie catégorie -->
    
    <div class="w-full h-fit flex flex-col gap-y-4">
        <div id="resto-header-container" class="h-10 flex justify-between items-center">
            <h3 id="header-title" class="text-xl text-[#182135] font-semibold flex items-center gap-1">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                 <path stroke-linecap="round" stroke-linejoin="round" d="M9.568 3H5.25A2.25 2.25 0 003 5.25v4.318c0 .597.237 1.17.659 1.591l9.581 9.581c.699.699 1.78.872 2.607.33a18.095 18.095 0 005.223-5.223c.542-.827.369-1.908-.33-2.607L11.16 3.66A2.25 2.25 0 009.568 3z" />
                 <path stroke-linecap="round" stroke-linejoin="round" d="M6 6h.008v.008H6V6z" />
                </svg>
                <span>Repas maison</span>
            </h3>
            <span id="see-more-resto" class="text-sm">Tout voir ></span>
        </div>
        <div id="first-category-container" class="h-fit w-full sm:w-full max-w-full grid sm:grid-cols-3 gap-y-8 sm:gap-4">

            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/crevette_1.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Crevettes</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>Resto du coeur</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge items-center text-[#fff] gap-1">
                            7.000F
                        </p>
                    </div>
                </div>
            </div>
            <!--  -->
            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/poulet_1.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Poulet entier</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>La Grill</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge items-center text-[#fff] gap-1">
                            5.500F
                        </p>
                    </div>
                </div>
            </div>
            <!--  -->
            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/attieke.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Attieke Alloco Poisson</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>Resto du coeur</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge items-center text-[#fff] gap-1">
                            2.500F
                        </p>
                    </div>
                </div>
            </div>
            <!--  -->
            <div class="h-64 sm:h-56 w-full grid cursor-pointer">
                <div class="w-full h-52 sm:h-44 relative overflow-hidden rounded-xl">
                    <img src="/images/pizza_1.jpg" alt="" class="h-full w-full max-w-full max-h-full object-cover rounded-xl hover:scale-125 duration-700">
                    <div class="bg-[#fff] absolute top-2 left-2 h-8 w-fit rounded-xl flex items-center px-2 gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#202020" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span class="text-xs font-semibold">30-45min</span>                          
                    </div>
                </div>
                <div class="w-full h-12 flex items-center justify-between">
                    <div class="flex flex-col">
                        <span class="text-xl sm:text-base font-semibold text-[#1F2937]">Burger Classique</span>
                        <div class="text-xs flex items-center text-[#A4A4A4] gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                          </svg>
                            <span>Resto du coeur</span>  
                        </div>
                    </div>
                    <div>
                        <div class="text-xs flex items-center justify-center gap-1">
                            <span class="text-sm">4.5</span> 
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="#f6e58d">
                                <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <p class="text-sm badge items-center text-[#fff] gap-1">
                            2.500F
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<style>
    .partner{
        display: grid;
        grid-template-columns: 96px 1fr;
    }
        @media screen and (max-width: 960px) {
            #partner-container{
                grid-template-columns: repeat(3, 288px);
            }

            #first-category-container{
                grid-template-columns: 1fr;
            }
        }
        ::-webkit-scrollbar{
            display: none;
        }
</style>