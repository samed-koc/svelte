

<script>
    let counter =$state(0)
    const increment = () => {
        counter += 1
    }
  let colorize ="orangered"

let content =`
<h1> Big banana exposed </h1>
<p> Lorem ipsum dolor sit amet adipisicing elit. Voluptas, doloremque! </p>
`

</script>

<button onclick={increment}>
  count is {counter}
</button>
    <h1 style:colorize>Hello world</h1>
    <h2 style:color={colorize}>Hello world</h2>
    <h3 style ="color:{colorize}">Hello world</h3>
<h4 >Hello world</h4>
<div>
    {@html content}
</div>
<style>
    button {
        font-size: 1.5em;
        padding: 0.5em 1em;
        margin: 0.5em;
        border: none;
        border-radius: 4px;
        background-color: #ff3e00;
        color: white;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }
    button:hover {
        background-color: #ff5722;
    }
    h4 {
        color: var(--color, blue);
    }
</style>