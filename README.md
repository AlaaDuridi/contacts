# React + Vite

### Simplicity of 'old school web'

```
 <Form> prevents the browser from sending the request to the server and sends it to your route action instead.

 after the action finishes, all of your useLoaderData hooks update and the UI stays in sync with your data automatically!
```

```
useNavigation returns the current navigation state: it can be one of "idle" | "submitting" | "loading".
```

```
avoid calling the loaders for unchanging routes (like the list) during a navigation.
```

```
Contextual errors:
User has more options than slamming refresh, He can continue to 
interact with the parts of the page that aren't having trouble 
```

```
Index routes:
When the route has children, and you are at the parent route's path, the <Outlet/>
has nothing to render because no children match.
The solution is to add an index route to the parent route.
```

```
<button type="button" > is the HTML way of preventing a button from submitting its form.
```

```
 The currentTarget is the DOM node the event is attached to, and the currentTarget.form is the input's parent form node.
 The submit function will serialize and submit any form you pass to it.
```