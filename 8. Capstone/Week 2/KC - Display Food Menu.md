### 1. As per Little Lemon's requirements, the menu items should be fetched from the server only once. The data is stored in an SQLite database and loaded from there when the subsequent app starts. What configuration allows you to retrieve the items only once?

- [ ] Using a useEffect hook with no dependencies.
- [ ] Using a useEffect hook with a dependency on a local state variable called items, which holds the array with the menu items.
- [x] Using a useEffect hook with no dependencies and a condition inside the effect that queries the SQLite database for data already stored.

### 2. Which of the code snippets would you use to fetch and render image from the network in React Native?

- [ ] ``` Image source={'url'}```
- [x] ```Image source={{url: (url) }} style={{width:'400', height:'400'}} />```
- [ ] ```Image source={{url: (url) }} />```

### 3. The requirement for Little Lemon’s hero banner search bar is to minimize the amount of database hits. This is to avoid querying the database too often, likeevery time a new character is typed, since it’s likely the user could type a new character right after and the previous query renders useless. What’s the best technique that allows you to accomplish this requirement?

- [ ] Using the JavaScript built-in interval function
- [ ] Using a debounce function
- [ ] Executing the transaction if a minimum of three characters are typed

### 4. What's the best place in a React Native application to create a table in an SQLite Database, if the table doesn't exist?

- [ ] Inside the render part of the component
- [ ] Outside of React Native components
- [x] Inside an useEffect hook with an empty array as dependencies

### 5. Image you would like to query all salads in the menu from an SQLite database table called ```menu_items```. To do that, you type the characters, “Sal”&nbsp;inside the hero banner search bar. Which of the following SQL statements performs this query correctly?

- [ ] <code>
  SELECT * <br>
  FROM menu_items <br>
  WHERE title='sal'
  </code>
- [ ] <code>
  SELECT * <br>
  FROM menu_items <br>
  WHERE title like 'sal'
  </code>
- [x] <code>
  SELECT * <br>
  FROM menu_items <br>
  WHERE title like '%sal%'
  </code>



