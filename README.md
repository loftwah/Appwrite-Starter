# 🚀 Appwrite-Starter
This initializer allows you to start creating projects with Appwrite faster.
I'll start working on this project in a week or two.

My current plan is to create a Vue.JS project that already has Appwrite and some additional stuff like Tailwind setup. I think utilising Vite.JS would allow for a better development experience and the option to extend this intializer to other frameworks at a later time, so I'll probably use that.

## The idea
1. User starts the initializer with the command `npm init appwrite-starter`
2. The user will be able to select optional dependencies (feel free to suggest some by creating an issue)
3. The user enters their Appwrite credentials
4. The script creates the project and writes the users credentials into a .env file
5. Now the user only has to `cd` into the folder and run `npm install`
6. At this point the project should be set up so that the user can instantly start creating components etc. without having to wory about setting up Appwrite or any of the selected dependencies


## Optional dependencies
These are the dependencies that I believe would be a great starting point

- Tailwind/WindiCSS
- Pinia (I find this more intuitive than Vuex, but I could probably offer both)
- TypeScript
- VueRouter
- unplugin-icons

## Feel free to open an issue if you have a feature request.
