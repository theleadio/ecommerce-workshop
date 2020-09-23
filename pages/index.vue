<template>
  <div class="flex-1 flex-col w-screen relative font-poppins">
    <HeaderContent>
      <template v-slot:grid-1>
        <Content class="bg-lead-yellow">
          <template v-slot:content>
            <div class="flex h-full">
              <div class="flex items-center my-auto">
                <Logo class="h-20 md:h-32 mt-6 mx-3"/>
                <div class="flex flex-col">
                  <span class="text-2xl md:text-4xl font-semibold tracking-wide text-gray-900">Full-Stack <br/> Web Development</span>
                  <span class="text-lg md:text-2xl font-light tracking-wide text-gray-900">Build Real-World Web Applications</span>
                </div>
              </div>
            </div>
          </template>
        </Content>
      </template>

      <template v-slot:grid-2>
        <Content class="bg-lead-yellow">
          <template v-slot:content>
            <div class="flex h-full">
              <div class="flex flex-col my-auto">
                <div class="text-2xl md:text-4xl text-center font-medium my-6">
                  What will I learn in 4 Days?
                </div>
                <div class="flex items-center my-2 px-4">
                  <i class="far fa-window-maximize md:text-3xl text-gray-900"></i>
                  <span class="text-md md:text-xl mx-4 tracking-wide text-gray-900">
                    USER INTERFACE FRONT END DEVELOPMENT
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fas fa-server md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    BACKEND API SERVER DEVELOPMENT
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fas fa-database md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    FIRESTORE ( UNSTRUCTURE DATABASE )
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fas fa-cloud-upload-alt md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    CLOUD HOSTING
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fab fa-github md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    GITHUB ( VERSION CONTROL )
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fas fa-user-lock md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    AUTHENTICATION
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fab fa-dev md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    WEB DEVELOPMENT FLOW
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fas fa-toolbox md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    WEB DEVELOPMENT TOOLBOX
                  </span>
                </div>
                <div class="flex items-center my-4 px-4">
                  <i class="fas fa-infinity md:text-3xl text-gray-900"></i>
                  <span class="md:text-xl mx-2 tracking-wide">
                    REFRESHER ( PHYSICAL CLASS )
                  </span>
                </div>
              </div>
            </div>
          </template>
        </Content>
      </template>

      <template v-slot:grid-3>
        <Content class="bg-lead-yellow">
          <template v-slot:content>
            <div class="flex h-full">
              <div class="flex flex-col items-center my-auto">
                <div class="text-2xl md:text-4xl text-center font-medium my-6">
                  Start from here
                </div>
                <img src="https://thelead-758c.kxcdn.com/wp-content/uploads/2018/08/full-stack-web-development-online-course.jpg" class="shadow-lg"/>
                <div class="my-10">
                  <a href="https://thelead.io/fs360livebonus" class="text-2xl py-2 px-8 bg-blue-600 hover:bg-blue-700 text-gray-100 hover:text-white font-light transition-all duration-500 ease-in-out cursor-pointer" target="_blank"> REGISTER </a>
                </div>
              </div>
            </div>
          </template>
        </Content>
      </template>

    </HeaderContent>
  </div>
</template>

<script>
export default {}
</script>
