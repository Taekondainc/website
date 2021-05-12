<template>
  <layout>
    <div class="grid  h-screen grid-cols-2">
      <div class="relative pt-8 grid   items-center ">
        <div class="leading-10">
          <h1 class="text-2xl tracking-wider">
            TAEKONDA CREATIVE AGENCY
          </h1>
          <h3 class="text-2xl">CONNECT, INNOVATE & EXPLORE.</h3>
          <p class="max-w-sm    leading-tight text-sm ">
            Creating solutions that innovate Digital Marketing whether it be
            Identity Design, UX / UI Design, Web & App Development, Social Media
            Marketing or Brand Strategy.
          </p>
          <a href="Connect" class="border-b-2   inline  mt-11 leading-1">
            Connect
            <g-image
              class="inline"
              src="~/assets/arrowup.png"
              height="15px"
              width="15px"
            />
          </a>
        </div>
        <clients />
        <div class="mb-10">icons</div>
      </div>
      <div class="relative pt-8 grid   items-center">hello</div>
    </div>
  </layout>
</template>

<script>
import clients from "~/components/clients";

export default {
  components: {
    clients,
  },
};
</script>
