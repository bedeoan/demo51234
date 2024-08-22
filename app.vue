<template>
  <div class="my-3">
    <div class="bg-red-600 text-white text-2xl text-bold pl-1 md:font-bold">SKAEBNER</div>
    <div class="flex row bg-gray-100 py-5 py-2">
      <div class="w-2/3 mt-2">
        <div class="mx-2 mb-5">
          <card
            url="/images/image1.png"
            title="EN LASER FORTALER"
            description="Jeg higede efter omsorg - del 2:5"
            :isVideo="true"
          />
        </div>
        <div class="flex row">
          <div class="w-1/2 mx-2">
            <card
              url="/images/image2.png"
              title="NAR LIVET GOR ONDT"
              description="33-arige Dagmar har maske kun fa maneder tilbage"
            />
          </div>
          <div class="w-1/2 mx-2">
            <card
              url="/images/image3.png"
              title="NAR LIVET GOR ONDT"
              description="Stinne og Cristian er uhelbredeligt syge med kraeft"
            />
          </div>
        </div>
      </div>
      <div class="w-1/3">
        <sofa />
      </div>
    </div>
  </div>
</template>
