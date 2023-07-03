# React vs. Svelte vs. Vue

> Examples in Vue that compliment [Fireship's React vs. Svelte](https://www.youtube.com/watch?v=MnpuK0MK4yo) video.

I watched [this interesting video](https://www.youtube.com/watch?v=MnpuK0MK4yo) about the differences between React and Svelte, and thought I would create complimentary examples using [Vue](https://vuejs.org/) and [Nuxt](https://nuxt.com/).

## Running the Examples

Clone the repository, then run the following steps:

```shell
$ pnpm install
# or npm i, etc.
$ pnpm dev -o
# or npx dev -- -o, etc.
```

The above code will install Nuxt and Vue, start the web server, then open up your default browser to `localhost:3000`.

You are meant to use your browser side-by-side with the code examples in this project, so you can see what is going on.

## Project Layout

All examples are in the `pages/` directory with the format of `##-name.vue`. `pages/index.vue` is the homepage. It contains links to all the examples and their respective sections of the video.

Each example will have a comment at the bottom that may look like this:

```vue
<!--
See:
    - ...
    - ...
-->
```

These are links to pages in Vue's (or Nuxt's) documentation describing the features used. Examples are meant to be read sequentially, so links made in previous examples will probably not be made again.

Some examples use components, which may look like this:

```vue
<template>
    <MyComponent />
</template>
```

You can find the component's source code in the `components/` directory. This example's component would be at `components/MyComponent.vue`. You can ignore the `components/a/` directory, it is not part of any examples.

All additional files and folders are not relevant to the examples, but are either required for the project to run or are quality-of-life for me.

If you have any questions, please feel free to [create a new issue in the issue tracker]().
