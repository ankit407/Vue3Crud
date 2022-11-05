<template>
  <div class="container mt-3">
    <div class="row">
      <div class="col">
        <p class="h3 text-success fw-bold">Add Contact</p>
        <!-- <p class="fs-italic">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, earum.
          Eaque reiciendis explicabo commodi pariatur quod quam repudiandae non.
          Deleniti, cum incidunt consequuntur obcaecati in perspiciatis debitis
          architecto vero exercitationem dignissimos tempore, accusantium totam?
          Reiciendis, provident nesciunt possimus nemo molestias enim quam
          dolores, earum esse commodi molestiae eligendi, ex tempora. Qui
          accusantium, fugiat dolores quaerat error nulla labore? Neque cum
          error explicabo quia debitis atque nostrum, culpa harum aperiam fugiat
          sequi dicta eveniet, eligendi placeat aut molestiae molestias. Nihil
          nisi repellat dolorum minima. Neque similique, ipsa dolores ad dolor
          laborum repellendus consectetur quisquam doloribus laboriosam ullam
          nemo, aliquid reprehenderit, repudiandae earum reiciendis voluptas
          dicta placeat quibusdam iste saepe. Recusandae explicabo asperiores
          deleniti, amet culpa inventore suscipit omnis nobis eum commodi non,
          similique at.
        </p> -->
      </div>
    </div>
  </div>
  <div class="container mt-3">
    <div class="row">
      <div class="col-md-3">
        <form>
          <div class="mb-2">
            <input type="text" class="from-control" placeholder="Name" />
          </div>
          <div class="mb-2">
            <input type="text" class="from-control" placeholder="Photo URL" />
          </div>
          <div class="mb-2">
            <input type="email" class="from-control" placeholder="Email" />
          </div>
          <div class="mb-2">
            <input type="number" class="from-control" placeholder="Mobile" />
          </div>
          <div class="mb-2">
            <input
              type="text"
              class="from-control"
              placeholder="Company Name" />
          </div>
          <div class="mb-2">
            <input type="text" class="from-control" placeholder="Title" />
          </div>
          <div class="mb-2">
            <select class="from-control">
              <option value="">Select Group</option>
            </select>
          </div>

          <div class="mb-2">
            <input type="submit" class="btn btn-primary" value="create" />
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    name: "AddContact",
  };
</script>
