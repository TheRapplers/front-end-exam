# Front-end programming exam
Instructions for Rappler's front-end developer programming exam

## Objective
Write a React component that renders latest news from rappler api as "stories" (like instagram stories).

- Use any React framework and bundler you deem necessary
- Integrate the following API endpoint (https://us-central1-rapplerinternal.cloudfunctions.net/latest-news) for the latest stories and fetch data from it to populate your component
- Make it responsive to mobile devices and desktop browsers
- Render an instagram stories like execution using images that can be found on the API and overlay the title on top.
- Use the best optimized image on the current screen size

## Bonus points (Optional)
- Add unit and component automation tests to your React component
- Deploy app on github pages or the likes
- Swipe up gesture to open the article

### Above and beyond (Even more optional)
- Build your React component in a way that it can be rendered server-side

## Expectations
- Demonstrate your knowledge of the React lifecycle and coding proficiency.
- Demonstrate your skill with designing HTML elements with CSS using any preprocessor you deem necessary

### API documentation

- The api contains the title, slug, images, and section of the story
- To create the link of the article, get the slug and the primary section and manipulate it in such a way it will look like this "https://rappler.com/section/slug". If the section of the article has a parent, the URL will look like this instead "https://rappler.com/parent/section/slug"


