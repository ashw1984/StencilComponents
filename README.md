# StencilComponents

These components are built using stencil. Please see the stencil site here for a better explaination.

A quick example can be found here https://jsfiddle.net/8hah0vu9/

To install this to an existing web project you can either use NPM or NUGET

To install with NPM please use the following command
npm install @ashw1984/style-guide-components
please then include the following files in any web output
node_modules/@ashw1984/style-guide-components/dist/style-guide-components.js
and files in the following folder
node_modules/@ashw1984/style-guide-components/dist/style-guide-components/*.js
NOTE:- this folder must be in the same location as the js file and have the same name.

Instructions for nuget to follow

If you want to see a running example of the following site please look at the following project
https://github.com/ashw1984/StencilComponentsTestSite

Once installer web components can simply be added using HTML for example the following tag would add the ternary-graph component to the body of the page.

<body>
 <ternary-graph></ternary-graph>
</body>
