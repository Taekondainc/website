<template>
    <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="layout">
    <div>
      <nav class="sticky top-0">
        <div class="max-w-full mx-auto sm:px-6 lg:px-14 flex items-center justify-between h-16 ">
          
            <div class="flex items-center">
              <div class="flex-shrink-0">
                
            <a href="/"> <g-image class="h-8 w-8"
                  src="~/assets/logodark.png"
                  alt="Workflow" /></a>  
              </div>
            </div>

            <div class="flex items-right">
              <div class="flex-shrink-0">
                <div class="ml-10 flex items-center space-x-8 text-white">
                  <a href="/Designs"  >Designs</a>
                  <a href="/Branding"  >Branding</a> 
                <div><g-image src="~/assets/menu.svg" /> </div>
                </div>
              </div>
            </div>
          
        </div>
      </nav>
      <main class="  px-14 text-white  " >    <slot /></main>
    </div>
<div class="max-w-full mx-auto sm:px-6 lg:px-14 flex items-center justify-between h-64 bg-white"><a href="home">home</a></div>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>

</style>
