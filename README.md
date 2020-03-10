

# sass-framework
Handmade sass framework using gulp // **School project**


#### How to start ? 
 

    $cd /PATH_TO_DIR/
    $npm install
    $gulp
   ~~You may need to use sudo~~
   
   ##### Output  :
   

    enter code heregulp.task('css-dev', () => {
    return gulp.src('./src/assets/*')
    .pipe(plugins.sass())
    .pipe(gulp.dest('./dist/assets/'))
    })
   
   ##### It will also start a watch function and browser-sync (with this config) :
   

    server: {
    baseDir: "./"},
    files : [
    'dist/**/*'],
    watchEvents : ['add', 'change', 'unlink', 'addDir', 'unlinkDir'],
    open : false,
    notify : false,
    ghostMode : false,
    ui: {
    port: 8001
    }}
![terminal preview](https://i.ibb.co/1vv7ttS/Untitled-2.png)


## What my framework provide you ?
Here is the list of classes you can use : 

**Basic columns :**

    .col-1 //From 1 to 12

**Medias queries for 3 screens sizes :** 

Large screen size : 
 

    .lg-1 //From 1 to 1O

Medium screen size :

    .md-1 //From 1 to 8

Small screen size :

    .sm-1 //From 1 to 4

**Text-align :** 

Align left 

    .text-left

Align right 

    .text-right

Align center

    .text-center

Justify 

    .text-justify

**Floats** 

Left

    .left

Right

    .right
    
**Justify Content**

Justify center

    .justify-center
Justify between

    .justify-between

**Align** 

Align Center

    .align-center

Align Start

    .align-start

Align End 

    .align-end

Align Stretch

    .align-stretch

Align Between

    .align-between

Align Around

    .align-around

**Padding :**

Global 

    .p-0 //From 0 to 4 (each *20px)
    
Top

    .pt-0 //From 0 to 4 (each *20px)
    
Bottom

    .pb-0 //From 0 to 4 (each *20px)
Right

    .pr-0 //From 0 to 4 (each *20px)
Left

    .pl-0 //From 0 to 4 (each *20px)

**Margin :**

Global 

    .m-0 //From 0 to 4 (each *20px)
    
Top

    .mt-0 //From 0 to 4 (each *20px)
Bottom

    .mb-0 //From 0 to 4 (each *20px)

Right

    .mr-0 //From 0 to 4 (each *20px)
Left

    .ml-0 //From 0 to 4 (each *20px)
    

**Sources :** 

[https://gulpjs.com/](https://gulpjs.com/)

[https://www.browsersync.io/](https://www.browsersync.io/)

[https://sass-lang.com/](https://sass-lang.com/)
