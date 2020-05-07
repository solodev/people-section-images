# people-section-images
When showcasing staff members or individuals on a page, it is often best to showcase a featured image with each person so that there is a human, personal look and feel.

## Tutorial
For detailed instruction's, view Solodev's [How to Add Featured Images to Your People Sectional for a Personal Touch](http://www.solodev.com/blog/web-design/how-to-add-featured-images-to-your-people-sectional-for-a-personal-touch.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/t6yphckf/).

## HTML
The tutorial contains the following basic HTML markup.

```
<section class="section mt-5 pb-5">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h2 class="h1 mb-4 mb-md-5 text-center text-md-left">Department Staff</h2>
        <div class="row custom">
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="box-information">
              <a href="#" class="no-arrow">
                <div class="image">
                  <img alt="Astromedicine - Veronica Gutierrez" class="img-fluid d-none d-md-block" src="https://raw.githubusercontent.com/solodev/people-section-images/master/images/Team_Doctor.jpg">
                </div>
                <div class="text">
                  Veronica Gutierrez
                  <span class="small d-block">Astromedicine practitioner</span>
                </div>
              </a>
            </div>
          </div>

          <div class="col-lg-4 col-sm-6 col-12">
            <div class="box-information">
              <a href="#" class="no-arrow">
                <div class="image">
                  <img alt="Lunar Life Sciences - Jacquelyn Li" class="img-fluid d-none d-md-block" src="https://raw.githubusercontent.com/solodev/people-section-images/master/images/Team_LifeSciences.jpg">
                </div>
                <div class="text">
                  Jacquelyn Li
                  <span class="small d-block">Lunar Life Sciences</span>
                </div>
              </a>
            </div>
          </div>

          <div class="col-lg-4 col-sm-6 col-12">
            <div class="box-information">
              <a href="#" class="no-arrow">
                <div class="image">
                  <img alt="XP-1 Base Operations - Adam Paul" class="img-fluid d-none d-md-block" src="https://raw.githubusercontent.com/solodev/people-section-images/master/images/Team_Commander.jpg">
                </div>
                <div class="text">
                  Adam Paul
                  <span class="small d-block">Base Operations</span>
                </div>
              </a>
            </div>
          </div>

        </div><!-- row custom -->
      </div><!-- col-12 -->
    </div><!-- row -->
  </div>
</section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```