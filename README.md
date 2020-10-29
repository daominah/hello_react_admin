# Hello React admin

## Init project

* Init a React app

````bash
export PROJECT=hello_react_admin
npx create-react-app ${PROJECT} --template typescript
````

* react-admin type [issue](https://github.com/marmelab/react-admin/issues/5247):

````bash
npm install typescript@3.9.7
````

* Add file [src/javascript.d.ts](src/javascript.d.ts):

````ts
declare module 'react-admin';
````

## Intro react-admin

[Tutorial.html](https://marmelab.com/react-admin/Tutorial.html)
