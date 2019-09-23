  <template>
  <Main>
  <div>
  <div class="container-about-me-in">
  <div>
  <h2>Apie mane</h2>
  <p>here are many variations of passages of Lorem Ipsum available,

but the majority have suffered alteration in some form, by injected humour,
or randomised words which don't look even slightly believable. If you
are going to use a passage of Lorem Ipsum, you need to be sure there isn't
anything embarrassing hidden in the middle of text. All the Lorem Ipsum
generators on the Internet tend to repeat predefined chunks as necessary,
here are many variations of passages of Lorem Ipsum available,
but the majority have suffered alteration in some form, by injected humour,
or randomised words which don't look even slightly believable. If you
are going to use a passage of Lorem Ipsum, you need to be sure there isn't
anything embarrassing hidden in the middle of text. All the Lorem Ipsum
generators on the Internet tend to repeat predefined chunks as necessary,
here are many variations of passages of Lorem Ipsum available,
but the majority have suffered alteration in some form, by injected humour,
or randomised words which don't look even slightly believable. If you
are going to use a passage of Lorem Ipsum, you need to be sure there isn't
anything embarrassing hidden in the middle of text. All the Lorem Ipsum
generators on the Internet tend to repeat predefined chunks as necessary,words etc.</p> 
</div>
  </div>
		<div class="secondary-navigation">
		<RouterLink class="router-link" :to="{ name: 'About:Education' }">
      Education
    </RouterLink>
	<RouterLink class="router-link" :to="{ name: 'About:Carrier' }">
      Carrier
    </RouterLink>
	<RouterLink class="router-link" :to="{ name: 'About:Skills' }">
      Skills
    </RouterLink>
      <RouterView></RouterView>
		</div>
	</div>
</Main>
</template>

<script>
import Main from '@/components/Main'
import routes from '@/routes'


export default {
  name: 'About',
  components: {
	Main
  },
  mounted () {
    console.log(this.$route.name)
  }
}

</script>

<style>

.router-link {
margin-right: 10px;
color: #000000;

}

.secondary-navigation {
width: 1077px;
height: 5px;
margin: 0 auto;
margin-top: 60px;

}

.container-about-me-in {
width: 1077px;
height: 175px;
position: relative;
margin: 0 auto;
padding-top: 30px;
}

</style>
