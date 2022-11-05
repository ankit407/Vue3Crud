<template>
  <div class="container mt-3">
    <div class="row">
      <div class="col">
        <p class="h3 text-black fw-bold">
          Contact Manager
          <router-link to="contacts/add" class="btn btn-primary btn-sm">
            <i class="fa fa-plus-circle"></i>
            New
          </router-link>
        </p>
        <p class="fst-italic">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatem
          tempora nemo tempore quisquam, quae at ea, cum alias, a similique
          debitis qui rerum eligendi officiis ipsam quibusdam. Aperiam,
          similique sint.
        </p>

        <form>
          <div class="row">
            <div class="col-md-6">
              <div class="row">
                <div class="col">
                  <input
                    type="text"
                    class="from-control"
                    placeholder="Search Name" />
                </div>
                <div class="col">
                  <input type="submit" class="btn btn-outline-dark" />
                </div>
              </div>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row">
      <div class="col-md-6 mt-4">
        <div class="card my-2 list-group-item-success shadow-lg">
          <div class="card-body">
            <div class="row align-items-center">
              <div class="col-sm-4">
                <img
                  src="data:image/png;base64,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"
                  alt=""
                  class="contact-img" />
              </div>
              <div class="col-sm-6">
                <ul class="list-group">
                  <li class="list-group-item">
                    Name :
                    <span class="fw-bold">Ankit</span>
                  </li>
                  <li class="list-group-item">
                    Email :
                    <span class="fw-bold">ankit@gmail.com</span>
                  </li>
                  <li class="list-group-item">
                    Phone :
                    <span class="fw-bold">7674988775</span>
                  </li>
                </ul>
              </div>
              <div
                class="col-sm-2 d-flex flex-column justify-content-center align-items-center">
                <router-link
                  to="/contacts/view/:contactId"
                  class="btn btn-warning my-1">
                  <i class="fa fa-eye"></i>
                </router-link>
                <router-link
                  to="/contacts/edit/:contactId"
                  class="btn btn-primary my-1">
                  <i class="fa fa-pen"></i>
                </router-link>
                <button class="btn btn-danger my-1">
                  <i class="fa fa-trash"></i>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    name: "ContactManager",
  };
</script>
