<h1 align="center">vue-dashboard-template</h1>

English | [中文](./README.zh-TW.md)
#### Characteristic function

- Routing configuration, state management mechanism (State supports local storage by default), encapsulated and perfect Axios and API management mechanism suitable for middle and background development
- It is very convenient to expand the theme configuration function, and supports three typical middle and background styles by default
- Routing configuration, state management mechanism (State supports local storage by default), encapsulated and perfect Axios and API management mechanism suitable for middle and background development
- For the three typical business tables of adding, deleting and modifying query, please see "CRUD table", "category table" and "tree table" in the "page column" for details
- The refresh function without route jump supports cache page refresh. At present, most frameworks do not support cache page refresh
- It is a convenient and extensible internationalization solution, and provides two sets of non internationalized basic templates and two sets of internationalized basic templates (TS version / JS version)
- Handwritten versions of various custom instructions
- For table common components and pop-up common components that have been verified by multiple middle and background businesses, please see "crud table", "category table" and "tree table" in the "page column" for details

#### Main technology

- MVVM framework：vue v3
- Engineering Management：vite v2
- UI framework：element-plus
- Router manage：vue-router v4
- State Manage ：vuex v4
- Data request：axios
- Utility library：@vueuse/core

## How to use

1. get the source code project

   ```
   git clone https://github.com/cmdparkour/vue-admin-box.git
   ```

   

2. install dependence via npm or yarn

   ```
   npm install
   ```

   

3. run in the development

   ```
   npm run dev 或 npm run start
   ```

   

4. build in production

   ```
   npm run build
   ```