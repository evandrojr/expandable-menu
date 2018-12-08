# Expandable Menu 

## Setting up:




### It supports up to three levels of hierarchy. Just add the menu's items you need to **this.item**

```

    this.items = [
        name: 'Marvel', children: [
            {
            name: 'Spider-man', children2: [
                    { name: 'Mary Jane', action: 'alert("My boyfriend")' },
                    { name: 'Uncle Ben' },
                    { name: 'Aunt May' },
                ]
            },
            { name: 'Hulk' },
           ]
        },
        {
        name: 'DC', children: [
                { name: 'Super-Man', action: 'alert("I am on the second level!")'},
                { name: 'Batman' },
            ]
        },
        {
            name: 'Top level - Without children 1', action: 'alert("no kids!!!")'
        },
        {
            name: 'Top level - Without children 2',
        },
    ]

```

## Styling 

### Change:

```
 <style>
    :scope {
      font-size: 2rem
    }

    h1 {
      color: blue
    }

    h2 {
      color: red
    }

    h3 {
      color: green
    }

    ul {
      color: #999
    }
  </style>
```

## All the rest

The rest is as simple as that and you can figure it out! 
Just check **index.html** and **menu.html**
