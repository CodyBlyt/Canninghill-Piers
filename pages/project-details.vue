<template>
  <div>
    <div>
      <div class="py-12 select-none bg-theme-700">
        <div class="text-xl font-semibold text-center text-white sm:text-4xl">
          Testt
        </div>
      </div>
      <section class="py-12">
        <div class="max-w-6xl px-4 mx-auto">
          <div class="p-6 bg-white rounded-lg shadow-lg">
            <div class="grid grid-cols-1 gap-6 sm:grid-cols-2">
              <div>
                <label class="block text-gray-500">Developer</label>
                <p>Singhaiyi Huajiang Amber Pte. Ltd.</p>
              </div>
              <div>
                <label class="block text-gray-500">Location</label>
                <p>How Sun Drive, Singapore</p>
              </div>
              <div>
                <label class="block text-gray-500">District</label>
                <p>District 19</p>
              </div>
              <div>
                <label class="block text-gray-500">Site Area</label>
                <p>Approx. 5,104.30 sqm / 54,942 sqft</p>
              </div>
              <div>
                <label class="block text-gray-500">Solicitor</label>
                <p>Allen &amp; Gledhill LLP</p>
              </div>
              <div>
                <label class="block text-gray-500">Project Account No.</label>
                <p>OCBC Ltd. for Project Account No. 712-600139-001</p>
              </div>
              <div>
                <label class="block text-gray-500">Architect</label>
                <p>RSP Architects Planners &amp; Engineers Pte. Ltd.</p>
              </div>
              <div>
                <label class="block text-gray-500">Main Contractor</label>
                <p>China Construction Development Co. Pte. Ltd.</p>
              </div>
              <div>
                <label class="block text-gray-500">M &amp; E Consultant</label>
                <p>Alpha Consulting Engineers Pte. Ltd.</p>
              </div>
              <div>
                <label class="block text-gray-500">Landscape Consultant</label>
                <p>COEN Design International Pte. Ltd.</p>
              </div>
              <div>
                <label class="block text-gray-500">Address</label>
                <p>31, 33 How Sun Park, Singapore</p>
              </div>
              <div>
                <label class="block text-gray-500">No. of Storeys</label>
                <p>2 Blocks of 5-Storey Residential Units</p>
              </div>
              <div>
                <label class="block text-gray-500">Tenure</label>
                <p>Freehold</p>
              </div>
              <div>
                <label class="block text-gray-500">No. of Lifts</label>
                <p>2 Passenger Lifts for Each Block</p>
              </div>
              <div>
                <label class="block text-gray-500">Bicycle Lots</label>
                <p>20</p>
              </div>
              <div>
                <label class="block text-gray-500">Motorcycle Lots</label>
                <p>4</p>
              </div>
              <div>
                <label class="block text-gray-500">Site Use</label>
                <p>Residential Flat Developement</p>
              </div>
              <div>
                <label class="block text-gray-500">Total No. of Units</label>
                <p>80 Residential Units</p>
              </div>
              <div>
                <label class="block text-gray-500">No. of Car Park Lots</label>
                <p>80 Parking Lots and 2 Accessible Lots</p>
              </div>
              <div>
                <label class="block text-gray-500">Security</label>
                <p>24 Hours Security Guard</p>
              </div>
              <div>
                <label class="block text-gray-500">Expected Date of TOP</label>
                <p>31 December 2021</p>
              </div>
              <div>
                <label class="block text-gray-500">Expected Date of Legal Completion</label>
                <p>31 December 2024</p>
              </div>
              
            </div>
          </div>
          <div class="py-4 italic text-center text-gray-500">
            (Project details for The Lilium may be subjected to change without prior notice)
          </div>
          <section class="py-6">
            <NuxtLink
              to="/location-map"
              class="
                inline-flex
                items-center
                justify-center
                w-full
                px-3
                py-3
                text-white
                transition
                rounded
                sm:px-0
                hover:bg-theme-900
                bg-theme-700
              "
            >
              Continue To Location Map
              <svg
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
                class="w-5 h-5"
              >
                <path
                  d="M13 6l6 6-6 6M5 6l6 6-6 6"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                ></path></svg
            ></NuxtLink>
          </section>
        </div>
      </section>
      <BookAppointment />
    </div>
  </div>
</template>
<script>
export default {}
</script>
