# A FullStack Notion Clone!

[VIDEO TUTORIAL](https://www.youtube.com/watch?v=ZbX4Ok9YX94)


The real-time database and Notion-style editor make this a powerful platform for organizing information and collaborating with others. Both light and dark modes coupled with full mobile responsiveness provide an accessible interface. Robust functionality like infinite children documents, file management, and authentication enable complex content structuring and access control. Design flourishes such as icons, an expandable sidebar, and cover images make the experience more visually engaging. Publishing notes to the web and creating landing pages facilitate sharing knowledge publicly. Overall, this is a feature-rich system for crafting beautiful, structured content while maintaining usability across devices. The ability to recover deleted files also provides a safety net for accidental data loss.

Key Features:

- Real-time database  🔗 
- Notion-style editor 📝 
- Light and Dark mode 🌓
- Infinite children documents 🌲
- Trash can & soft delete 🗑️
- Authentication 🔐 
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time) 🌠
- Expandable sidebar ➡️🔀⬅️
- Full mobile responsiveness 📱
- Publish your note to the web 🌐
- Fully collapsable sidebar ↕️
- Landing page 🛬
- Cover image of each document 🖼️
- Recover deleted files 🔄📄

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone TopRIght duhh
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```
