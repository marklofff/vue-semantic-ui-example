<template>
  <div>
    <div class="ui huge menu">
  <a class="active item">
    Home
  </a>
  <a class="item">
    Messages
  </a>
  <div class="right menu">
    <div class="ui dropdown item">
      Language <i class="dropdown icon"></i>
      <div class="menu">
        <a class="item">English</a>
        <a class="item">Russian</a>
        <a class="item">Spanish</a>
      </div>
    </div>
    <div class="item">
        <div class="ui primary button">Sign Up</div>
    </div>
  </div>
</div>
    <h4 class="ui header">
      <a href="/elements/button.html">Button</a>
    </h4>
    <div class="button demo">
      <div class="ui button">
        View
      </div>
      <div class="ui primary button">
        <i class="shop icon"></i> Add to Cart
      </div>
      <div class="ui secondary button">
        <i class="save icon"></i> Save for Later
      </div>
      <div class="ui labeled icon button">
        <i class="star icon"></i>
        Rate
      </div>
      <div class="ui basic button">Basic</div>

      <div class="ui hidden divider"></div>

      <div class="ui animated button">
        <div class="visible content">Horizontal</div>
        <div class="hidden content">
          Hidden
        </div>
      </div>
      <div class="ui vertical animated button">
        <div class="visible content">Vertical</div>
        <div class="hidden content">
          Hidden
        </div>
      </div>
      <div class="ui animated fade button">
        <div class="visible content">Fade In</div>
        <div class="hidden content">
          Hidden
        </div>
      </div>

      <div class="ui hidden divider"></div>

      <div class="ui facebook button">
        <i class="facebook icon"></i>
        Facebook
      </div>
      <div class="ui twitter button">
        <i class="twitter icon"></i>
        Twitter
      </div>
      <div class="ui google plus button">
        <i class="google plus icon"></i>
        Google Plus
      </div>

      <div class="ui hidden divider"></div>
      <div class="ui buttons">
        <div class="ui button">1</div>
        <div class="ui button">2</div>
        <div class="ui button">3</div>
      </div>


      <div class="ui buttons">
        <div class="ui button">Cancel</div>
        <div class="or"></div>
        <div class="ui positive button">Save</div>
      </div>

      <div class="ui icon buttons">
        <div class="ui button"><i class="align left icon"></i></div>
        <div class="ui button"><i class="align center icon"></i></div>
        <div class="ui button"><i class="align right icon"></i></div>
        <div class="ui button"><i class="align justify icon"></i></div>
      </div>
      <div class="ui hidden divider"></div>
      <div class="ui blue button">Blue</div>
      <div class="ui red button">Red</div>
      <div class="ui teal button">Teal</div>
      <div class="ui blue basic button">Blue</div>
      <div class="ui red basic button">Red</div>
      <div class="ui teal basic button">Teal</div>

      <div class="ui inverted segment">
        <div class="ui inverted button">Inverted</div>
        <div class="ui inverted blue button">Blue</div>
        <div class="ui inverted red button">Red</div>
        <div class="ui inverted basic button">Basic</div>
        <div class="ui inverted blue basic button">Blue</div>
        <div class="ui inverted red basic button">Red</div>
      </div>

      <div class="ui hidden divider"></div>

      <div class="ui vertical buttons">
        <div class="ui button">Feed</div>
        <div class="ui button">Messages</div>
        <div class="ui button">Events</div>
        <div class="ui button">Photos</div>
      </div>

      <div class="ui vertical buttons">
        <div class="ui button">1</div>
        <div class="ui button">2</div>
        <div class="ui button">3</div>
      </div>

      <div class="ui vertical icon buttons">
        <div class="ui button"><i class="align left icon"></i></div>
        <div class="ui button"><i class="align center icon"></i></div>
        <div class="ui button"><i class="align right icon"></i></div>
        <div class="ui button"><i class="align justify icon"></i></div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
	mounted(){
		$(this.$el).find('.dropdown').dropdown()
	}
}
</script>
