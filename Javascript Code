<input id = "input">
<button  onclick="additem()"> Add</button>
<ul id="list">
    <li>
        todolist:
    </li>
</ul>

<script>
    var list = document.getElementById("list")
    var input = document.getElementById("input")
    function additem()
    {
        var additem = document.createElement("li")
        additem.innerHTML = input.value +"<button onclick='deleteItem(event)'>Delete</button>"
        list.append(additem)
    }
    function deleteItem(event)
    {
        event.target.parentElement.remove()
    }
</script>
