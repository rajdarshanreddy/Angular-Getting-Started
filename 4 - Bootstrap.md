# Bootstrap

## Step 1: Install Bootstrap

```sh
npm install --save bootstrap
```

## Step 2: Adding Bootstrap

Open the file `angular.json` and add `bootstrap.min.css` by adding below lines of code in `styles` sections as shown below.

```sh
"styles": [
        ---------------
        "node_modules/bootstrap/dist/css/bootstrap.min.css",
        ---------------
        ],
```

adding below lines of code in `scripts` sections as shown below.

```sh
"scripts": [
              "node_modules/jquery/dist/jquery.min.js",
              "node_modules/bootstrap/dist/js/bootstrap.min.js"
            ],
```

## Step 3: Check if Bootstrap Works

adding below lines of code in `index.html`

```sh
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        Woohoo, you're reading this text in a modal!
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```
run the application using `ng serve --open`, you should see a model when you click on the button `Launch demo modal`.


## References and Resources

Below are links to the documents that you can refer if you have any queries.

* https://getbootstrap.com/docs/4.2/getting-started/download/
* https://getbootstrap.com/docs/4.2/components
* https://getbootstrap.com/docs/4.2/examples/
