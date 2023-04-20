
<script>
    const name = 'Fredrik';
    let favorites = ['Wafles', 'Comedy', 'Football'];
    let about_me = {name, favorites}; 
</script>

<p>My name is {about_me.name} and these are some of my favourite things:
<ul>
    <li> {about_me.favorites[0]} </li>
    <li> {about_me.favorites[1]} </li>
    <li> {about_me.favorites[2]} </li>
</ul>

<ul>
    {#each about_me.favorites as obj}
    <li> {obj} </li>
    {/each}
</ul>
