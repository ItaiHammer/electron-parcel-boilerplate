<div  style="display: flex;flex-direction: row;align-items: center;justify-content: center;" >

<a style="outline: none;" href="https://github.com/ItaiHammer/electron-parcel-boilerplate" >
	<img src="README-picture.png"  alt="drawing"  width="1000"/>
</a>

</div>

<br/>

Electron Parcel Boilerplate uses: [Parcel](https://parceljs.org/), [Concurrently](https://www.npmjs.com/package/concurrently), [Sass](https://www.npmjs.com/package/sass), [wait-on](https://www.npmjs.com/package/wait-on), and [Electron](https://www.electronjs.org/).

# Install

First, clone the repo via git and install dependencies:

```sh

git clone https://github.com/ItaiHammer/electron-parcel-boilerplate.git your-project-name

cd your-project-name

npm i

```

# Commands

### Main Commands:

`npm start` - Starts a Parcel server and runs an Electron app running on the server

`npm run build` - Builds the Parcel app and creates an Electron app using the build for your current OS

### Package Specific Commands:

`npm run parcel:dev` - Runs a Parcel server

`npm run parcel:build` - Builds the Parcel app

`npm run electron:start` - Starts an Electron app using the build

`npm run electron:dev` - Starts an Electron app using the a parcel server

### Build Commands:

`npm del-dist` - Delets the dist folder

`npm del-cache` - Delets the cache folder

`npm del-build` - Delets the dist and cache folder

`npm create-blank-dist` - Creates a dist folder with a blank HTML file

`npm create-blank-cache` - Creates a blank cache folder

`npm create-blank-build` - Creates a blank cache folder and a dist folder with a blank HTML file

# Maintainer

-   [Itai Hammer](https://github.com/ItaiHammer)

# License

MIT © [Electron React Boilerplate](https://github.com/ItaiHammer/electron-parcel-boilerplate)
