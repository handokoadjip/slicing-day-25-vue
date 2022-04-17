<template>
  <section>
    <div class="container-fluid">
      <div class="row" v-for="(list, index) in lists" :key="index" :id="list.title">
        <div :class="`col-lg-6 d-flex align-items-center ${index % 2 === 0 ? 'order-1' : 'order-1 order-lg-0'}`">
          <div :class="`wrapper mx-5 mb-5 mb-lg-0 ${index % 2 === 0 ? 'text-start' : 'text-end'}`">
            <h2 class="text-capitalize fw-medium">{{list.title}}</h2>
            <p class="leading-loose text-fade-1 mb-4">{{list.description}}</p>
            <router-link class="text-decoration-underline fw-medium" :to="list.href">
              View Project
            </router-link>
          </div>
        </div>
        <div
          :class="`col-lg-6 mb-5 mb-lg-0 min-vh-50 ${list.image} ${index % 2 === 0 ? 'order-0' : 'order-0 order-lg-1'}`">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
  data() {
    return {
      lists: [
        {
          image: "bg-image-2",
          title: "Deo Architect",
          description:
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo mollitia voluptates modi esse doloremque ea a repellendus, officiis ipsam inventore.",
          href: "#",
        },
        {
          image: "bg-image-3",
          title: "IU Lorena",
          description:
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo mollitia voluptates modi esse doloremque ea a repellendus, officiis ipsam inventore.",
          href: "#",
        },
        {
          image: "bg-image-4",
          title: "Blocks MIO",
          description:
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo mollitia voluptates modi esse doloremque ea a repellendus, officiis ipsam inventore.",
          href: "#",
        },
        {
          image: "bg-image-5",
          title: "The Circle",
          description:
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo mollitia voluptates modi esse doloremque ea a repellendus, officiis ipsam inventore.",
          href: "#",
        },
        {
          image: "bg-image-6",
          title: "Black & Gray",
          description:
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo mollitia voluptates modi esse doloremque ea a repellendus, officiis ipsam inventore.",
          href: "#",
        },
        {
          image: "bg-image-7",
          title: "Arch But",
          description:
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo mollitia voluptates modi esse doloremque ea a repellendus, officiis ipsam inventore.",
          href: "#",
        },
      ]
    }
  }
}
</script>