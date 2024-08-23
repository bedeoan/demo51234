<template>
  <div class="my-3">
    <div class="bg-red-600 text-white text-2xl font-bold pl-1">
      SKAEBNER
    </div>
    <div class="flex bg-gray-100 py-5 px-2">
      <div class="w-2/3 mt-2 mr-2">
        <div class="mb-3">
          <card
            url="/images/image1.png"
            title="EN LASER FORTALER"
            description="Jeg higede efter omsorg - del 2:5"
            :isVideo="true"
          />
        </div>
        <div class="flex">
          <div class="w-1/2 mr-1">
            <card
              url="/images/image2.png"
              title="NAR LIVET GOR ONDT"
              description="33-arige Dagmar har maske kun fa maneder tilbage"
            />
          </div>
          <div class="w-1/2 ml-1">
            <card
              url="/images/image3.png"
              title="NAR LIVET GOR ONDT"
              description="Stinne og Cristian er uhelbredeligt syge med kraeft"
            />
          </div>
        </div>
      </div>
      <div class="w-1/3 flex justify-end">
        <div class="w-4/5">
          <sofa />
        </div>
      </div>
    </div>
  </div>
</template>
