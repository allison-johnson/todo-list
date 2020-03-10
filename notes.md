Javascript: Where to put this?

$(function(){
    $("input.toggle").on("change", function(){
        $(this).parents("form").trigger("submit")
    })
});

class="<%= "completed" if item.complete? %>"

<%= "checked='checked'" if item.complete? %>