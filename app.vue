<template>
    <div class="grid grid-cols-4 p-2 gap-4 min-h-screen">
        <div class="bg-gray-300 row-span-3"></div>
        <div class="bg-gray-300 col-span-2 row-span-2 rounded-lg h-full">
          <NuxtLayout>
            <NuxtPage />
          </NuxtLayout>
        </div>
        
      
        <div class="bg-gray-300 row-span-3 rounded-lg h-full">

        <WrapsItem />
        <WrapsItem />
        <WrapsItem />

        </div> 
        
        <div class="bg-gray-300 rounded-lg h-full col-span-2">

            <MenuItem />

        </div>

        <div class="bg-gray-300  h-30 col-span-4 px-4">

            <div class="flex gap-2 justify-center items-center h-full">
                <div class="flex-auto bg-lime-600 h-20">

                    <!--

                    <img id="logo" src="~/assets/images/aberhallo.png" width="300" alt="">

                    -->


                </div>
                <div class=" bg-lime-600 w-20 h-20"></div>
            </div>
        </div>
    </div>
</template>