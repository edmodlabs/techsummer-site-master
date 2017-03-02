# TechStart Online Manual

## Deployment

This will run deploy the site to local node server (localhost:4000):

    npm start

To deploy this to production, THIS WILL MAKE LIVE CHANGES (techstart.github.io):
    
    npm run deploy

## File Structure

### /src 
All content pages live here

### /src/docs 
All of the versioned content for projects live here

### /themes
where partial templates live

### /themes/techstart/layout/partials/examples/sidebar_header.ejs
where our sidebar partial template lives

### /themes/techstart/layout/partials/ga.ejs
analytics javascript

### /src/images/
Where our images live

to reference an image, such as **/images/docs/intro_vizor/blender.gif** 
add 
```
   <img src="/images/docs/intro_vizor/belnder.gif">
```
to your markdown page

## Adding Notices
```
<br/>
<div class="alert_red">
  <strong>Info!</strong> Indicates a neutral informative change or action.
</div>

<br/>
<div class="alert_blue">
  <strong>Warning!</strong> Indicates a warning that might need attention.
</div>

<br/>
<div class="alert_green">
  <strong>Danger!</strong> Indicates a dangerous or potentially negative action.
</div>

<br/>
<div class="alert_yellow">
  <strong>Danger!</strong> Indicates a dangerous or potentially negative action.
</div>
```
## Credits

Website source code adopted from the incredible [@aframe](https://aframe.io) [site](https://github.com/aframevr/aframe-site)
 and [@vuejs](https://vuejs.org) [site](https://github.com/vuejs/vuejs.org/).
## License

Licensed under [The MIT License](LICENSE).
