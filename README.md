# Tessellate Mosaic Demo

Demo of Tessellate and Mosaic Tailor.

### Instructions

Install all dependencies:

```sh
yarn install
```

Start the three services separately form one another: 

```sh
yarn run bundler
yarn run fragment
yarn run tailor
```

Post the content:

```sh
./scripts/post_content.sh
```

View the rendered template in your browser: [localhost:3005/hello](http://localhost:3005/hello)
