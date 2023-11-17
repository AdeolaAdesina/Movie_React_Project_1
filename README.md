# Movie_React_Project_1

## Set up React Application

Using the create-react-app command. You need to have node.js installed.

```
npx create-react-app movie-app
```

Run the application with:

```
npm start
```

Let's explore the file and folder structure of a react application.

![Screenshot_41](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/202ffbda-9e70-4fc0-9459-0c65aead1c05)

Package.json is where all the packages are located:

![Screenshot_42](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/2baad0ea-4313-4b5c-8ea9-187985b1ecb0)

The scr folder is where all the logic goes. app.css, app.js, index.js are all here.

The public folder houses all the public facing files like index.html, logo, favicon etc.

We can now clean up our index.html file:

![Screenshot_43](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/92d665b8-0fe1-428f-a800-4fa594245432)

It has a single div with an id of ```root```. All of our components are going to get injected inside this div.

Then we go to src/index.js. The starting point of every react.js application.

![Screenshot_44](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/fa33000e-f422-4ff8-a76d-58161540b24a)

Here we have the react DOM, which we only call once inside our application, no matter how big it is.

The root renders the app component in App.js.

![Screenshot_44](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/6c9e9084-3dc0-40e2-b7d8-0bfad21befbb)

We have our first functional component that returns JSX code.

In html, we have class, in JSX we have className.

Now let's clear the content of this component and have Hello world.

![Screenshot_46](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/9904cf19-e9f3-4ab0-80a0-e76e51221abb)

## Variables in components

Now let's pass a variable inside our component:

![Screenshot_47](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/b9a6a21e-5787-4b85-923b-9a1c98dfeddb)


Now let's add a Ternary expression:

![Screenshot_48](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/8791f150-3fcd-4509-bb12-78d4cfc9080a)

We can play around with a react fragment. 

![Screenshot_49](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/056fe9e1-cda2-4b25-a441-90342c628e1f)

We can either play with an empty react fragment or give it a JSX.

![Screenshot_50](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/be084e39-b573-408d-af1a-2da1f5aebca1)

And if we want to add an H2, we will need to wrap around a major JSX element or a react fragment.

![Screenshot_51](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/967ccc27-7cd3-475d-9b8d-b28bbcbe1a02)


## Components interacting with components

See how we created a person component and passed it into App component

![Screenshot_52](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/3b6082da-708f-40d8-a7cb-66c4f85e4188)

One advantage of this is that we can duplicate the referenced component multiple times.

![Screenshot_53](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/3fd19891-b360-4ce9-bb6a-6e79d49d33b7)


## Using props to pass data dynamically

Props are just arguments that you pass into react components. They're passed via attributes.

![Screenshot_54](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/0ccdeb2a-0dfb-4579-a2e9-baa749a291cd)

You will notice that only the first component has a name.

Now let's complete the first component:

![Screenshot_55](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/47a08ef9-b401-4180-a011-a42ce8f437cf)

A string is also acceptable:

![Screenshot_56](https://github.com/AdeolaAdesina/Movie_React_Project_1/assets/29931071/c2942c6d-3560-40bf-a4be-e0c7adfe9d3b)









