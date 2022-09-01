<script>
  import { Check, OpenInNew } from "mdue"

  export default {
    name: "App",
    components: {
      Check,
      OpenInNew
    }
  }
</script>

<template>
  <div class="flex justify-center items-center h-[100vh] select-none">
    <div class="bg-[#2c2c2c] w-full mx-4 sm:max-w-[400px] h-fit rounded-lg shadow-2xl">
      <div class="relative">
        <div class="bg-[#fc1703] w-full h-20 rounded-t-lg absolute top-0"></div>
        <div class="relative top-4 left-4 max-w-fit">
          <img class="z-10 rounded-full border-[8px] border-[#2c2c2c] h-36" src="./assets/icon.png" alt="icon">
          <div class="bg-green-700 h-5 w-5 right-4 bottom-4 absolute rounded-full outline-[#2c2c2c] outline-[6px] outline"></div>
        </div>
        <div class="right-4 h-7 w-7 absolute top-[94px] bg-[#242424] rounded-lg p-[2px]">
          <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><g fill="#2ea967"><path d="m8.1176653 16.0847263 4.8330812-8.1694527h2.9315882l-4.8330812 8.1694527z"/><path d="m20.4189453 9.4038086v-2.4311524c0-1.9775391-1.0825195-3.1118164-2.9697266-3.1118164h-1.5581055v1.7802734l.9594727-.0014648c.8540039 0 1.34375.5683594 1.34375 1.5585938v2.3969727c0 .8300781.1806641 1.8422852 1.5893555 2.3100586l.2856445.0947265-.2856445.0947266c-1.4086914.4677734-1.5893555 1.4799804-1.5893555 2.3100586v2.3964844c0 .9907227-.4897461 1.559082-1.34375 1.559082l-.9594727-.0014648v1.7802734h1.5581055c1.887207 0 2.9697266-1.1342773 2.9697266-3.1118164v-2.4316406c0-1.2583008.3432617-1.6264648 1.5810547-1.6445312v-1.9023438c-1.237793-.0180665-1.5810547-.3862305-1.5810547-1.6450196z"/><path d="m5.8061523 7.1982422c0-.9760742.5024414-1.5585938 1.3432617-1.5585938l.9594727.0014648v-1.7802734h-1.5576172c-1.887207 0-2.9697266 1.1342773-2.9697266 3.1118164v2.4311523c0 1.2587891-.3432617 1.6269531-1.581543 1.6450195v1.9023438c1.2382812.0180664 1.581543.3862305 1.581543 1.6445312v2.4316406c0 1.9775391 1.0825195 3.1118164 2.9697266 3.1118164h1.5576172v-1.7802734l-.9594727.0014648c-.8408203 0-1.3432617-.5830078-1.3432617-1.559082v-2.3964844c0-.8300781-.1806641-1.8422852-1.5898438-2.3100586l-.2856444-.0947264.2856445-.0947266c1.4091797-.4677734 1.5898437-1.4799804 1.5898437-2.3100586z"/></g></svg>
        </div>
      </div>
      <div class="px-4 pb-4 flex flex-col relative">
        <div class="flex items-center mt-8 text-2xl font-bold">
          <h1>UnoSlash</h1>
          <h1 class="text-[#bebebede]">#2313</h1>
          <div class="text-sm bg-[#5865F2] px-1 rounded-sm ml-1 flex justify-center items-center font-semibold">
            <Check class="mr-1"></Check>
            <p>BOT</p>
          </div>
        </div>
        <div class="text-center mt-5 bg-[#5865F2] hover:bg-[#4853d6] rounded-sm transition-colors">
          <a class="w-full flex justify-center items-center" target="_blank" href="https://discord.com/api/oauth2/authorize?client_id=1002203084388315146&permissions=274878254080&scope=applications.commands%20bot">
            <p class="p-2 font-semibold">Adicionar ao Servidor</p>
            <OpenInNew></OpenInNew>
          </a>
        </div>
        <div class="text-center mt-4 bg-[#5865F2] hover:bg-[#4853d6] rounded-sm transition-colors">
          <a class="w-full flex justify-center items-center" target="_blank" href="https://discord.gg/mKQzH89vP2">
            <p class="p-2 font-semibold">Servidor de Suporte</p>
            <OpenInNew></OpenInNew>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  body {
    color: #ffffffde;
    background-color: #242424;
  }
</style>