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

## Step 3: Check if Angular Material Works

            
        
