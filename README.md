# sveltestrap tabs

This is a simple solution of Bootstrap taps issue.


## Get started

```bash
yarn add hazg/sveltestrap-tabs
```

```svelte
<script>
  import { Tabs, TabHeader, Tab, TabContent, TabContentItem } from "sveltestrap-tabs"
</script>

<Tabs defaultId="one">

  <TabHeader>
    <Tab id="one">One</Tab>
    <Tab id="two">Two</Tab>
  </TabHeader>

  <TabContent>
    <TabContentItem id="one">
      first tab content
    </TabContentItem>
    <TabContentItem id="two">
      second tab content
    </TabContentItem>
  </TabContent>
</Tabs>
```


## Author

Original author: [@sonjoydatta](https://github.com/sonjoydatta) for more info.

Fork author: [@hazg](https://github.com/hazg)

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/sonjoydatta/sveltestrap-tabs/blob/master/LICENSE) file for details.