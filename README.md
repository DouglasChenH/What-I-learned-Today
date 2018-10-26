# What-I-learned-Today
Note for coding related experience

# Table of contents
1. [2018](#year_2018)
    1. [October](#month_Oct)
2. [2019](#year_2019)
    

## 2018 <a name="year_2018"></a>
### October <a name="month_Oct"></a>
  #### Oct 24
  1. File names must be all lowercase and may include underscores (_) or dashes (-), but no additional punctuation.
  2. Use const and let instead of var for JavaScript
  
  #### Oct 25
  1. Passing a Boolean in the Props (Vue.js)
  ``` bash
    <!-- Including the prop with no value will imply `true`. -->
    <blog-post is-published></blog-post>

    <!-- Even though `false` is static, we need v-bind to tell Vue that -->
    <!-- this is a JavaScript expression rather than a string.          -->
    <blog-post v-bind:is-published="false"></blog-post>

    <!-- Dynamically assign to the value of a variable. -->
    <blog-post v-bind:is-published="post.isPublished"></blog-post>
       
  ```
  #### Oct 26
  1. Vue.js v-for can use an alias called index to render a list of items and track their indexes. Alternatively, we can use $index
  ``` bash
    <div v-for="(index, item) in items">
      {{ index }} {{ item.message }}
    </div>
       
  ```
___
