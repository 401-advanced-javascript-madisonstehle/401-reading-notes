# Class-22
## React Testing & Deployment

### Links
- [Jest Testing with React](https://create-react-app.dev/docs/running-tests/)
- [Snapshot Testing](https://jestjs.io/docs/en/snapshot-testing)
- [Static Rendering - Enzyme](https://enzymejs.github.io/enzyme/docs/api/render.html)
- [Shallow Mounting - Enzyme](https://enzymejs.github.io/enzyme/docs/api/shallow.html)
- [Full Mounting - Enzyme](https://enzymejs.github.io/enzyme/docs/api/mount.html)
- [AWS S3 Deployment](https://www.youtube.com/watch?v=Kay-UvVCNFs) (video)
- [AWS Amplify Deployment](https://www.youtube.com/watch?v=DHLZAzdT44Y) (video)
- [Netlify Deployment](https://www.youtube.com/watch?v=sGBdp9r2GSg) (video)


### Discussion Questions
1. **Describe a case where snapshot testing would be useful, and describe another case where it would be ineffective.** Snapshot tests are effective once the UI page is fully developed and won't change much if at all. They are ineffective when the app is still in development.
2. **What is the difference between full mount and shallow mount?** Full mounting allows rendering an entire component and its children components, but shallow mounting focuses on fully rendering only the current component.
3. **What does npm run build do?** Builds an application depending on the script in the package.json. In the case of react apps, build can bundle and minimize files. and optimized the build.


#### [Back to Home](README.md)