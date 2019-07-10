<template>
    <footer>
        <grid>
            <row class="row">
                <column :xs="0" :md="0" :lg="3">
                </column>
                <column :xs="12" :md="4" :lg="3">
                    <ul>
                        <li class="title">Service</li>
                        <li><a href="">Free videos</a></li>
                        <li><a href="">Tools, Apps and plugins</a></li>
                        <li><a target="_blank" href="https://dribbble.com/Freebieboss">Designer</a></li>
                        <li><a target="_blank" href="https://dribbble.com/shots/5377148-Multipurpose-Theme">Project Page</a></li>
                        <li><a target="_blank" href="https://nikandlv.ir">Nikandlv</a></li>
                        <li><a target="_blank" href="https://github.com/nikandlv/lybra-vue">Github</a></li>
                    </ul>
                </column>
                <column :xs="12" :md="4" :lg="3">
                    <ul>
                        <li class="title">Popular</li>
                        <li><a href="">Portfolio</a></li>
                        <li><a href="">Downloads</a></li>
                        <li><a href="">Blog</a></li>
                        <li><a href="">Photos</a></li>
                        <li><a href="">FAQ</a></li>
                        <li><a href="">API</a></li>
                    </ul>
                </column>
                <column :xs="12" :md="4" :lg="3">
                    <ul class="simple">
                        <li class="title">Contacts</li>
                    </ul>
                    <p>50 Raritan Center Pkwy, Edison, NJ 088464, USA</p>
                    <div class="icon-text">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
                            <path id="ic_call_24px" d="M6.62,10.79a15.149,15.149,0,0,0,6.59,6.59l2.2-2.2a.994.994,0,0,1,1.02-.24,11.407,11.407,0,0,0,3.57.57,1,1,0,0,1,1,1V20a1,1,0,0,1-1,1A17,17,0,0,1,3,4,1,1,0,0,1,4,3H7.5a1,1,0,0,1,1,1,11.36,11.36,0,0,0,.57,3.57,1,1,0,0,1-.25,1.02Z" transform="translate(-3 -3)"/>
                        </svg>
                        <p>09300000000</p>
                    </div>
                    <div class="icon-text">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="16" viewBox="0 0 20 16">
                            <path id="ic_email_24px" d="M20,4H4A2,2,0,0,0,2.01,6L2,18a2.006,2.006,0,0,0,2,2H20a2.006,2.006,0,0,0,2-2V6A2.006,2.006,0,0,0,20,4Zm0,4-8,5L4,8V6l8,5,8-5Z" transform="translate(-2 -4)"/>
                        </svg>
                        <p>nikandalvand@gmail.com</p>
                    </div>
                    <div class="button-group">
                        <a class="divider" href="">Contact us</a>
                        <a href="">Visit us</a>
                    </div>
                </column>
            </row>
        </grid>
    </footer>
</template>
<style lang="stylus" scoped>
@media(max-width:800px)
  footer
    padding 1rem !important
    li
      margin 25px 0 !important
    .row
      flex-direction column-reverse
footer
  padding 1rem 6rem
  ul
    .title,.title-simple
      font-weight bold
      font-size 1.4rem
      margin-bottom 48px
    &.simple
      padding-left 0
      .title
        margin-left 0
    li
      display block
      margin 24px 40px
      a
        text-decoration none
        color black
        font-size 0.9rem
        transition color 300ms
        &:hover,&:focus,&:active
          color #6c63ff
  .icon-text
    display flex
    align-items center
    p
      margin-left 1rem
  .button-group
    margin-top 24px
    white-space nowrap
    display inline-block
    border 1px solid black
    padding 0
    border-radius 8px
    .divider
      border-right 1px solid black
    a
      padding 1rem 2rem
      display inline-block
      color black
      text-decoration unset

</style>
