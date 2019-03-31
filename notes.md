https://www.youtube.com/watch?v=yCcWpzY8dIA

What questions would a "serverless CMS" be responsible for answering? (Access patterns)

- Let's start simple
    - What pages do I have? 
        - What are on those pages?

TableName: Pages
PrimaryIndex: Hash

```
<div class="parent">
    <div class="content--container">
        <h1 class="title">{TITLE]</h1>
        <p class="title--supporting-text">
        <img src="{uri}" class="img-class" />
        <a href="{url}" class="link" >
    </div>
</div>
```

```
<form> 
    <input />
    <label />
    <button type="submit">
</form>
```

```
.content--container {
    .title {
        /* Attributes */
    }
    &--supporting-text {
        /* Attributes */
    }
    .img-class {
        b
    }
    a {

    }
}
```

elements | List
elements: [{}, {}, {}]

new PageTable({})

How to create "globally" unique ids?

element | String
attributes: 

Pages
{
    id: <HASH>
    elements: [
        {
            element: 'p',
            attributes: {
                'class': [
                    'text',
                    'textOther'
                ]
            },
            children: {

            }
        }
    ]
}


What would a rendering service be responsible for? 
- Turning representation into valid markup



