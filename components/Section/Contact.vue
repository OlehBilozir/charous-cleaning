<template>
  <div
    class="bg-aliceBlue min-h-screen mx-auto | grid place-content-center | text-center"
  >
    <div class="container">
      <UIPrimaryHeading title="Contact Us" />

      <div class="rounded-lg shadow-lg bg-white py-12 max-w-[100%] mx-auto">
        <section class="mb-24 text-gray-800">
          <div class="flex flex-wrap">
            <div
              class="grow-0 shrink-0 basis-auto mb-6 md:mb-0 w-full md:w-6/12 px-3 lg:px-6"
            >
              <p class="text-gray-500 mb-6 max-w-prose">
                Thank you for considering Charous Cleaning for all of your pool
                maintenance needs. To get in touch with us, please use the
                following information:
              </p>
              <p class="text-gray-400 mb-2">Lane Cove, 2066, Australia</p>
              <p class="text-gray-400 mb-2">+ 01 234 567 89</p>
              <p class="text-gray-400 mb-6">info@charouscleaning.com</p>
              <p class="text-gray-500 mb-2 max-w-prose">
                If you prefer, you can also fill out the contact form on our
                website and a member of our team will respond to your inquiry as
                soon as possible. We look forward to hearing from you and
                providing you with the best pool cleaning services in the area.
                Thank you!
              </p>
            </div>
            <div
              class="grow-0 shrink-0 basis-auto mb-12 md:mb-0 w-full md:w-6/12 px-3 lg:px-6"
            >
              <form>
                <div class="form-group mb-6">
                  <input
                    type="text"
                    class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                    id="exampleInput7"
                    placeholder="Name"
                  />
                </div>
                <div class="form-group mb-6">
                  <input
                    type="email"
                    class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                    id="exampleInput8"
                    placeholder="Email address"
                  />
                </div>
                <div class="form-group mb-6">
                  <textarea
                    class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                    id="exampleFormControlTextarea13"
                    rows="3"
                    placeholder="Message"
                  ></textarea>
                </div>
                <div class="form-group form-check text-center mb-6">
                  <input
                    type="checkbox"
                    class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain mr-2 cursor-pointer"
                    id="exampleCheck87"
                    checked
                  />
                  <label
                    class="form-check-label inline-block text-gray-800"
                    for="exampleCheck87"
                    >Send me a copy of this message</label
                  >
                </div>
                <button
                  type="submit"
                  class="w-full px-6 py-2.5 bg-blue-600 font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out"
                >
                  Send
                </button>
              </form>
            </div>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionContact",
};
</script>

<style lang="scss" scoped></style>
