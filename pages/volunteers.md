## THIS IS FOR PROFILE PHOTOS :D

```js data-import="./volunteer_data.coffee"
const volunteer_data = require('./volunteer_data.coffee');

<!-- Render the data using Markdown -->
<ul>
    {volunteer_data.contributors.map(contributor => (
        <li key={contributor.name}>
            <strong>{contributor.name}</strong>
            <br />
            Profile: <a href={contributor.profileURL}>{contributor.profileURL}</a>
        </li>
    ))}
</ul>




```markdown
<!-- Include the generated Markdown content -->
<!-- Start generated_content.md -->
### People Information

<!-- End generated_content.md -->
```js data-import="./volunteer_data.coffee"
const volunteer_data = require('./volunteer_data.coffee');

<!-- Render the data using Markdown -->
<ul>
    {volunteer_data.contributors.map(contributor => (
        <li key={contributor.name}>
            <strong>{contributor.name}</strong>
            <br />
            Profile: <a href={contributor.profileURL}>{contributor.profileURL}</a>
        </li>
    ))}
</ul>




```markdown
<!-- Include the generated Markdown content -->
<!-- Start generated_content.md -->
### People Information

<!-- End generated_content.md -->

