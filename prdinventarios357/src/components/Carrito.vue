const newLocal='Carrito'
<template>
  <div>
    <div class="container"></div>

    <h2 class="text-center">Carrito de compra</h2>
    <div class="row">
      <div class="mb-3 col-md-6">
        <label class="form-label" for="inputLastName">Total</label>
        <input
          type="text"
          class="
            bg-light
            border-start-0 border-end-0 border-top-0
            form-control
            ps-0
            pe-0
            rounded-0
          "
          id="inputLastName"
          placeholder="$"
        />
      </div>
      <div class="mb-3 col-md-6">
        <button
          type="submit"
          class="
            btn btn-primary
            float-right
            pl-4
            pr-4
            rounded-0 rounded-pill
            text-uppercase
          "
        >
          <span class="align-middle">FINALIZAR PEDIDO</span>
          <svg
            viewBox="0 0 24 24"
            fill="currentColor"
            height="16"
            width="16"
            class="ml-1"
          >
            <path
              d="M1.946 9.315c-.522-.174-.527-.455.01-.634l19.087-6.362c.529-.176.832.12.684.638l-5.454 19.086c-.15.529-.455.547-.679.045L12 14l6-8-8 6-8.054-2.685z"
            ></path>
          </svg>
        </button>
      </div>
    </div>
    <section class="pb-5 pt-5 text-black-50">
      <div class="container">
        <div class="justify-content-center row">
          <div class="col-lg-4 col-md-6 pb-3 pt-3">
            <div class="bg-light border overflow-hidden rounded-3">
              <a
                href="#"
                class="
                  border border-start-0 border-end-0 border-top-0
                  d-block
                  position-relative
                "
                ><div
                  class="
                    d-flex
                    flex-row-reverse
                    justify-content-between
                    p-3
                    position-absolute
                    start-0
                    top-0
                    w-100
                  "
                >
                  <span class="badge bg-danger fw-normal rounded-pill"
                    >New</span
                  >
                  <span class="badge bg-primary fw-normal rounded-pill"
                    >10% off</span
                  >
                </div>
                <img
                  src="https://images.unsplash.com/photo-1600100999954-10751954d931?ixid=MXwyMDkyMnwwfDF8c2VhcmNofDU0MHx8Z3JheSUyMHByb2R1Y3R8ZW58MHx8fA&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=240&fit=crop"
                  class="img-fluid w-100"
                  alt="..."
                  width="300"
                  height="240"
              /></a>
              <div class="pb-3 ps-4 pe-4 pt-3">
                <div class="align-items-center row">
                  <div class="col-sm pb-2 pt-2">
                    <a href="#" class="text-dark text-decoration-none"
                      ><h3 class="h5 mb-1">Product Name</h3></a
                    >
                    <p class="mb-0 small">Short description</p>
                  </div>
                  <div class="col-sm-auto pb-2 pt-2">
                    <p class="fw-light h4 mb-0">$129</p>
                  </div>
                </div>
                <div class="pb-2 pt-2">
                  <a class="btn btn-primary btn-sm ps-3 pe-3" href="#"
                    >Add to Cart</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 pb-3 pt-3">
            <div class="bg-light border overflow-hidden rounded-3">
              <a
                href="#"
                class="
                  border border-start-0 border-end-0 border-top-0
                  d-block
                  position-relative
                "
                ><div
                  class="
                    d-flex
                    flex-row-reverse
                    justify-content-between
                    p-3
                    position-absolute
                    start-0
                    top-0
                    w-100
                  "
                >
                  <span class="badge bg-danger fw-normal rounded-pill"
                    >Hot Sale</span
                  >
                </div>
                <img
                  src="https://images.unsplash.com/photo-1571151329817-d4d5b6c35771?ixid=MXwyMDkyMnwwfDF8c2VhcmNofDU4NHx8Z3JheSUyMHByb2R1Y3R8ZW58MHx8fA&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=240&fit=crop"
                  class="img-fluid w-100"
                  alt="..."
                  width="300"
                  height="240"
              /></a>
              <div class="pb-3 ps-4 pe-4 pt-3">
                <div class="align-items-center row">
                  <div class="col-sm pb-2 pt-2">
                    <a href="#" class="text-dark text-decoration-none"
                      ><h3 class="h5 mb-1">Product Name</h3></a
                    >
                    <p class="mb-0 small">Short description</p>
                  </div>
                  <div class="col-sm-auto pb-2 pt-2">
                    <p class="fw-light h4 mb-0">$129</p>
                  </div>
                </div>
                <div class="pb-2 pt-2">
                  <a class="btn btn-primary btn-sm ps-3 pe-3" href="#"
                    >Add to Cart</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 pb-3 pt-3">
            <div class="bg-light border overflow-hidden rounded-3">
              <a
                href="#"
                class="
                  border border-start-0 border-end-0 border-top-0
                  d-block
                  position-relative
                "
                ><div
                  class="
                    d-flex
                    flex-row-reverse
                    justify-content-between
                    p-3
                    position-absolute
                    start-0
                    top-0
                    w-100
                  "
                >
                  <span class="badge bg-primary fw-normal rounded-pill"
                    >20% off</span
                  >
                </div>
                <img
                  src="https://images.unsplash.com/photo-1609900179119-3ed9f4530eb8?ixid=MXwyMDkyMnwwfDF8c2VhcmNofDY1N3x8Z3JheSUyMHByb2R1Y3R8ZW58MHx8fA&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=240&fit=crop"
                  class="img-fluid w-100"
                  alt="..."
                  width="300"
                  height="240"
              /></a>
              <div class="pb-3 ps-4 pe-4 pt-3">
                <div class="align-items-center row">
                  <div class="col-sm pb-2 pt-2">
                    <a href="#" class="text-dark text-decoration-none"
                      ><h3 class="h5 mb-1">Product Name</h3></a
                    >
                    <p class="mb-0 small">Short description</p>
                  </div>
                  <div class="col-sm-auto pb-2 pt-2">
                    <p class="fw-light h4 mb-0">$129</p>
                  </div>
                </div>
                <div class="pb-2 pt-2">
                  <a class="btn btn-primary btn-sm ps-3 pe-3" href="#"
                    >Add to Cart</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Carrito",
  props: {
    msg: String,
  },
};
</script > 
<style scoped>
h3 {
  margin: 40px 0 0;
}

h1 {
  margin: 40px 0 0;
}
</style> 
