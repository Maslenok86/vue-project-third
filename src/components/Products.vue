<script>
import {products} from "../products";
</script>

<template>
  <div class="flex justify-center my-[100px]">
    <div class="flex flex-col w-[1300px]">
      <div class="flex justify-between items-center w-full mb-[40px]">
        <div class="text-5xl">продукция</div>
        <button class="bg-zinc-100 p-[10px]">смотреть все</button>
      </div>
      <div class="flex items-center w-full gap-[10px]">
        <button class="bg-zinc-100 p-[10px] focus:bg-amber-500">пирожные</button>
        <button class="bg-zinc-100 p-[10px] focus:bg-amber-500">слойка</button>
        <button class="bg-zinc-100 p-[10px] focus:bg-amber-500">хлеб</button>
      </div>
      <div class="flex border overflow-x-auto w-full h-[300px] mt-[40px] gap-[10px]">
        <div class="flex shrink-0 flex-col h-[250px] w-[220px] gap-[10px]">
          <div class="relative">
            <img
                src="https://imgproxy.bushe.ru/2vWzzZe1jEZhOSjKGE5Tov4wrOdj1lP1F-v_rXrtl8M/q:85/w:440/h:336/rt:fill/el:1/czM6Ly9idXNoZS9tZWRpYS9Qcm9kdWN0L2ltYWdlcy9iY2IwZmIzYi0zN2ViLTQ3YWQtOWM1Mi0yMGUwNWNjZTBkMDIvY2QxM2YzZDZmYjY3MWRkMmJjMmI5ZWJjMTgyNTg0MzkuanBn.webp">
            <div class="benefit-form absolute bottom-0 left-0 bg-amber-500 text-sm p-[3px] pr-[10px]">
              популярные
            </div>
          </div>
          <div class="">Пирожное Эклер Ванильный</div>
          <div class="flex gap-[5px]">
            <div class="text-lg items-center font-semibold">160₽</div>
            <button class="border text-gray-300 font-semibold text-sm p-[5px]">70г</button>
          </div>
        </div>
        <div class="flex shrink-0 flex-col h-[250px] w-[220px] gap-[10px]">
          <div class="relative">
            <img
                src="https://imgproxy.bushe.ru/hGjnd2LyFsXwiJV3bJ81Bm6_rTLccozi8bbFDPxZK5g/q:85/w:440/h:336/rt:fill/el:1/czM6Ly9idXNoZS9tZWRpYS9Qcm9kdWN0L2ltYWdlcy9lMDU2NTk1OS0yM2M0LTQ2ZDEtYWM1ZS0xZDQ2ZjI5NjJiZGMvMGZkYjA5ZmMxNmZhNWM3ODFlM2VkZTFjMDUyZjhkMjQucG5n.webp">
            <div class="benefit-form absolute bottom-0 left-0 bg-lime-500 text-sm p-[3px] pr-[10px]">
              vegan
            </div>
          </div>
          <div class="">Пирожное Кешью-кейк Манго</div>
          <div class="flex gap-[5px]">
            <div class="text-lg items-center font-semibold">260₽</div>
            <button class="border text-gray-300 font-semibold text-sm p-[5px]">85г</button>
          </div>
        </div>
        <div class="flex shrink-0 flex-col h-[250px] w-[220px] gap-[10px]">
          <div class="relative">
            <img
                src="https://imgproxy.bushe.ru/HFcL3eTqcXvSE2d8czGWP7GVl4T2-soiPFSjzQdnh98/q:85/w:440/h:336/rt:fill/el:1/czM6Ly9idXNoZS9tZWRpYS9Qcm9kdWN0L2ltYWdlcy8xNzU1MjM3My1iYWM2LTQ2MjktODg3Yy03ZWYxMzMzNDYyNzEv0YDQuNC60L7RgtGC0LgucG5n.webp">
            <div class="benefit-form absolute bottom-0 left-0 bg-amber-500 text-sm p-[3px] pr-[10px]">
              с ягодами
            </div>
          </div>
          <div class="">Пирожное Рикотти Клубника</div>
          <div class="flex gap-[5px]">
            <div class="text-lg items-center font-semibold">160₽</div>
            <button class="border text-gray-300 font-semibold text-sm p-[5px]">95г</button>
          </div>
        </div>
        <div class="flex shrink-0 flex-col h-[250px] w-[220px] gap-[10px]">
          <div class="relative">
            <img
                src="https://imgproxy.bushe.ru/bSqwUyXOIKJgVKS-Wv8WUMGhC2XWu-R4kM1JX4Xtte4/q:85/w:440/h:336/rt:fill/el:1/czM6Ly9idXNoZS9tZWRpYS9Qcm9kdWN0L2ltYWdlcy80NzAzOTAzNC0wNWNhLTRjMjItOTZkNS00YTRlM2VkZDRlMmEv0YjRgy3QsdGD0LfQuNC90LAt0YfQtdGA0L3QsNGPLdGB0LzQvtGA0L7QtNC40L3QsC3QvdC-0LLQuNC90LrQsC5qcGc.webp">
            <div class="benefit-form absolute bottom-0 left-0 bg-amber-500 text-sm p-[3px] pr-[10px]">
              новинки
            </div>
          </div>
          <div class="">Пирожное Шу Бузина-Черная Смородина</div>
          <div class="flex gap-[5px]">
            <div class="text-lg items-center font-semibold">230₽</div>
            <button class="border text-gray-300 font-semibold text-sm p-[5px]">80г</button>
          </div>
        </div>
        <div class="flex shrink-0 flex-col h-[250px] w-[220px] gap-[10px]">
          <div class="relative">
            <img
                src="https://imgproxy.bushe.ru/CKzlD6pXSB0h8UGR1Mt9QGu95KmU07dDswOuT7mv9WU/q:85/w:440/h:336/rt:fill/el:1/czM6Ly9idXNoZS9tZWRpYS9Qcm9kdWN0L2ltYWdlcy85OTI4ZDQ4MC03M2JkLTQ4ODEtYmQxNy1hMzk0NWExNzVmZmUvMmJkYmNjNDE1ZjA1ZTIyMDRlM2E5M2U2MmRhZTEyODQuanBn.webp">
            <div class="benefit-form absolute bottom-0 left-0 bg-amber-500 text-sm p-[3px] pr-[10px]">
              популярные
            </div>
          </div>
          <div class="">Пирожное Бушель (желтый)</div>
          <div class="flex gap-[5px]">
            <div class="text-lg items-center font-semibold">170₽</div>
            <button class="border text-gray-300 font-semibold text-sm p-[5px]">80г</button>
          </div>
        </div>
        <div class="flex shrink-0 flex-col h-[250px] w-[220px] gap-[10px]">
          <div class="relative">
            <img
                src="https://imgproxy.bushe.ru/j739Pf6mxRUAQimP29tw1EouHMdO7nX3YRFBXeWTNdI/q:85/w:440/h:336/rt:fill/el:1/czM6Ly9idXNoZS9tZWRpYS9Qcm9kdWN0L2ltYWdlcy80M2E0NTQwMi1hMjk2LTQyZmUtOTIyMC1mNzkwZTM0NTdjNjQvYTE0MzE0MDc0NmY0ZTQ0OWJiMjQ2MzRjMzNiY2YwZDQuanBn.webp">
            <div class="benefit-form absolute bottom-0 left-0 bg-amber-500 text-sm p-[3px] pr-[10px]">
              с ягодами
            </div>
          </div>
          <div class="">Пирожное Рикотти Малина</div>
          <div class="flex gap-[5px]">
            <div class="text-lg items-center font-semibold">160₽</div>
            <button class="border text-gray-300 font-semibold text-sm p-[5px]">85г</button>
          </div>
        </div>
        <div class="flex shrink-0 flex-col h-[250px] w-[220px] gap-[10px]">
          <div class="relative">
            <img
                src="https://imgproxy.bushe.ru/K_tIv8hSfCNbQwk6XnIdFoiu0kYgJoV1RPzk6IinWRM/q:85/w:440/h:336/rt:fill/el:1/czM6Ly9idXNoZS9tZWRpYS9Qcm9kdWN0L2ltYWdlcy84ZDFjNTJhNi1hMTEwLTQ1ODEtYjI3MS02MzQwZGM5MWRkMTcvN2RjMmNjOTlkMGI5OTBlZjM0M2U0YzcxZGU4YzE5OTkuanBn.webp">
            <div class="benefit-form absolute bottom-0 left-0 bg-amber-500 text-sm p-[3px] pr-[10px]">
              с ягодами
            </div>
          </div>
          <div class="">Пирожное Мильфей</div>
          <div class="flex gap-[5px]">
            <div class="text-lg items-center font-semibold">270₽</div>
            <button class="border text-gray-300 font-semibold text-sm p-[5px]">130г</button>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>

<style scoped>
.benefit-form {
  /*https://atuin.ru/tools/clip-path/*/
  clip-path: polygon(0% 0%, 100.00% 0.00%, 95% 50%, 100.00% 100%, 0.00% 100%);
}
</style>