<template>
  <div class="">
    <section
      class="is-relative is-flex is-flex-direction-row-reverse is-justify-content-center"
    >
      <div
        class="is-hidden-touch is-flex is-align-items-center is-justify-content-center is-w-half-desktop has-background-primary"
      >
        <div class="is-fullwidth is-max-w-lg">
          <img
            class="is-fullwidth"
            src="metis-assets/illustrations/walk-dog.png"
            alt=""
          />
        </div>
      </div>
      <div class="section pt-5 pb-6 is-fullwidth is-w-half-desktop">
        <div>
          <div class="mb-6 is-flex is-justify-content-space-between">
            <a href="#"
              ><img
                src="metis-assets/logos/metis/metis.svg"
                alt=""
                width="106"/></a
            ><router-link class="button is-primary is-outlined" to="/login"
              >Sign in</router-link
            >
          </div>
          <div>
            <span class="subtitle is-spaced">Sign Up</span>
            <h4 class="title is-size-3">Create an account</h4>
            <div class="field is-horizontal">
              <div class="field-body">
                <div class="field">
                  <div class="control">
                    <input class="input" type="text" placeholder="First name" />
                  </div>
                </div>
                <div class="field">
                  <div class="control">
                    <input class="input" type="text" placeholder="Last name" />
                  </div>
                </div>
              </div>
            </div>
            <div class="mb-5">
              <div class="field">
                <div class="control has-icons-right">
                  <input
                    class="input"
                    type="email"
                    placeholder="name@email.com"
                  />
                  <span class="icon is-small is-right">
                    <svg
                      class="image is-24x24"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewbox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"
                      ></path>
                    </svg>
                  </span>
                </div>
              </div>
              <div class="field">
                <div class="control has-icons-right">
                  <input
                    class="input"
                    type="password"
                    placeholder="Enter your password"
                  />
                  <span class="icon is-small is-right">
                    <svg
                      class="image is-24x24"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewbox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                      ></path>
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"
                      ></path>
                    </svg>
                  </span>
                </div>
              </div>
              <div class="field">
                <div class="control">
                  <button class="button is-primary is-fullwidth">
                    Sign Up
                  </button>
                </div>
              </div>
            </div>
            <div>
              <p>
                <a href="#">Police privacy</a> and <a href="#">Terms of Use</a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
