<template>
  <div class="container">

    <header >
      <bread-crumbs/>
    </header>

    

    <div class="row">
      <div class="car-title col-sm-9">
        Nissan Pathfinder ST 2017
      </div>
    </div>

    <labels/>
    <div class="row">
      <div class="col-sm-9">
        <div class="row">
          <hero-video/>
        </div>
        <div class="info-badges row">
          <div class="col-sm-4">
            <img src="../assets/off-road.png"/>
          </div>
          <div class="col-sm-4">
            <img src="../assets/daily-driver-score.png"/>
          </div>
          <div class="col-sm-4">
            <img src="../assets/off-road-score.png"/>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4">
            <img src="../assets/synopsis.png"/>
          </div>
          <div class="content-body col-sm-8">
            <div class="nav-buttons row">
              <div class="btn btn-light col-sm-4">
                Book A Test Drive
              </div>
              <div class="btn btn-light col-sm-4">
                Download A Brochure
              </div>
              <div class="btn btn-light col-sm-4">
                Locate A Dealer
              </div>
            </div>
            <div class="text=body">
              <h2>daily driver review</h2>
              <p>
                <strong>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit,  exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </strong>
              </p>

              <p>
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
              </p>

              <p>
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
              </p>

              <div class="more-reviews">
                <h5>More Nissan Pathfinder reviews</h5>
                <ul>
                  <li><a href="#">Nissan Pathfinder 2011</a></li>
                  <li><a href="#">Nissan Pathfinder 2012</a></li>
                  <li><a href="#">Nissan Pathfinder 2013</a></li>
                  <li><a href="#">Nissan Pathfinder 2014</a></li>
                  <li><a href="#">Nissan Pathfinder 2015</a></li>
                </ul>
              </div>

              <p>
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
              </p>

              <p>
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
              </p>
            </div>
          </div>
        </div>
         
      </div>
      <div class="sidebar-ads col-sm-3">
        <a href="#">
          <img src="../assets/pathfinder-ad.png"/>
        </a>
        <a href="#">
          <img src="../assets/audi-ad.png"/>
        </a>
        <a href="#">
          <img src="../assets/related-cars.png"/>
        </a>
      </div>
    </div>    
  </div>
</template>

<script>
/* Todo: modularise above strucutre by defining them in their own reusable vue componenets
*/
import BreadCrumbs from './BreadCrumbs'
import Labels from './Labels'
import HeroVideo from './HeroVideo'

export default {
  name: 'Container',
  components: {
    BreadCrumbs,
    Labels,
    HeroVideo
  },
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

@media (min-width: 576px){
  .col-sm-9 {
    max-width: 1290px;
    flex:0 0 75%;
  }
}
.info-badges {
  margin-top:20px;
  div {
    padding-right:0px;
  }
  img {
    width:100%;
  }
}
.sidebar-ads {
  img {
    padding-bottom:20px;
  }
}

.car-title {
  font-size: 3em;
  font-weight: 500;
}

.content-body {
  .nav-buttons {
    margin-left: 0px;
    margin-right: -15px;
    margin-top:20px;
    .btn {
      width: 20%;
    }
    
    .btn-light{
      border-color: #ffcbb8;
    }
  }
}

.more-reviews {
  background-color: #f6f6f6;
  padding: 1em;
  height: 8rem;
  margin-bottom: 20px;
  h5 {
    padding-left:20px;
  }

  ul {
    display: flex;
    flex-wrap: wrap;
    li {
      width: 50%;
      a {
        color: black;
        font-size: 0.8em;
      }
    }
  }
}
</style>
