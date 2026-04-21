# Assignment-8

### Implementation of Vue Router

The Vue Router was implemented to enable navigation between different pages of the website without requiring full page reloads from the DOM, the router was 'built' in a dedicated `router/index.js` file, where routes were mapped out to specific components where each route was given a path and it was linked to a corresponding view component which allowed the app to render content based on the URL. The router was integrated into the app through `main.js` using `.use(router)`, enabling routing functionality and easy access across the entire project.

### Pages and Structure

The application consists of two main views:
- **Home.vue** – this serves as the default landing page which is displayed at the root path 
- **About.vue** – this is an additional page accessible from the `/about` route

These pages were stored in a `views` folder to separate the full-page components from smaller reusable components. The navigation between these pages is handled using the `<router-link>` tag, while `<router-view>` in `App.vue` acted as the dynamic container where routed components were displayed!

### Importance of Routing in Single-Page Applications

Routing is an important part of single-page applications because it allows the app to behave like a multi-page website without needing to reload the entire page over and over. Instead of loading new HTML files from the server, Vue Router changes what is shown on the screen based on the URL automatically. This makes navigation faster and creates a smoother user experience.

Without routing, a single-page application would only be able to show one fixed, static page, which would make it less useful and harder to expand. Vue Router helps modern web applications feel like traditional websites with multiple pages, while still keeping the speed and efficiency of a single-page app.


### Challenges and Insights

During development of the project I encountered some challenges in correctly connecting the different parts of the Vue Router setup. As each file plays a specific role in the overall structure of the app i needed to research a lot to fully grasp the concept of it and eventually got caught up in a furstrating mess of errors and paths that did not work.

At times, debugging configuration issues and working through many unexpected errors made the process feel complex and slightly overwhelming. However, these challenges also encouraged me to slow down and develop a clearer understanding of how the different pieces of a Vue application fit together. I started over many times to fully understand each step carefully but i think i eventually overcomplicated the process a lot..

Despite the difficulties, this process was valuable in building familiarity with the framework. It helped me better understand how routing is structured and how components are dynamically rendered based on the application state and URL. Over time, I was able to recognise patterns in how Vue applications are organised, which improved my overall comprehension of the system but i will continue improving and researching to successfully complete it in the next assignment!

### Conclusion

Although I experienced difficulties during the process and did not achieve a fully smooth setup, the project improved my theoretical understanding of Vue Router and SPA architecture. Further practice is definitely required to strengthen my ability to independently implement and debug routing configurations in future projects. I will continue to work and improve on it!
