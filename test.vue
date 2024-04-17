<template>

<html>
<head>
	
  
</head>
<body>

	<div id="threediv"></div>

    <div id="divvy">

		
        <h1 id="name"></h1>
		<div id="namername"></div>
    </div>

    <div id="disc">

    </div>

    <VCard id="droppedclass">
		
		

        <div id="intro">
            
			<VCard id="iframecapture"></VCard>
            

			<iframe id='iframe' src="https://www.youtube.com/embed/1CPHIWi4SA8?si=pYYDIpqSR09gcylB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

            
        </div>
		<VCard id="capturebackgroundsolutionpresentdata"></VCard>
		<VCard id="capturebackgrounds">
			
		</VCard>
		<VCardTitle id="capturetitle">Unlimited Money Glitch 1.0.1</VCardTitle>
		<div id="capturetitles"></div>
		<VCard id="capturebackground">
			<VCardTitle id="uppy">News/Updates</VCardTitle>
			<div id="capturebackgroundselve"></div>
				
			<VCard id="Validation">
				<VCardTitle id="deadwrong">Online.</VCardTitle>
				<div id="deadwrongstare">
					<v-infinite-scroll height = '275' id="apper" color="green">
						<VRow>
							<v-col id= 'textappear' v-for='n in allplayers' :key="n" cols="4" class="spacing-playground pa-0">
								<VCard id="appear">
									<VCardSubtitle id="sp">{{n.p_name}}</VCardSubtitle>
								</VCard>
								
							</v-col>
						</VRow>
					</v-infinite-scroll>

				</div>
				<VCardSubtitle id="vali">{{Intl.NumberFormat().format(NUMUSERS)}} Online </VCardSubtitle>
				<div id="surname"></div>
			</VCard>
			<VCard id="ValidationEager">
				<v-infinite-scroll id="carl" height="150" >
					<li id='inst' v-for="items in firstint">
						{{ items }}
					</li>
				</v-infinite-scroll>
				<v-infinite-scroll id="carl" height="150">
					<li v-for="items in updateslog">
						{{ items }}
					</li>
				</v-infinite-scroll>
				<VCard id="carlugly">Total Money Available: {{Intl.NumberFormat().format(NUMUSERS)}} $</VCard>
				<label id="carluglyson">Per participant.</label>
			</VCard>
			
		</VCard>
		<VCard id="capturebackgroundreal">
			<VCard id="capturebackgroundsolvent">
				<VCardSubtitle id="captitle">Season 1</VCardSubtitle>
				
			</VCard>

			<VCard id="capturebackgroundsolvents"  >
				<VCard id="depositbutton">
					<VCardSubtitle id="movedeposit">Deposit / Withdrawals</VCardSubtitle>
				</VCard>
				
				<VCard id="capturebackgroundsolventss">
				
				</VCard>
			</VCard>
			
			
			
		</VCard>

		<VCard id="capturebackgroundsolution"></VCard>
		<div id="capturebackgroundsolutiondata"></div>

		<VCard id="capturebackgroundsolutionpresent">
			
		</VCard>
		
		
        <div id="firstdrop">


        </div>

        <div id="god">
            
        </div>

        <div id="dropclass"></div>

		<VCard id="withdrawdepo" @click='GOWINDOWS'></VCard>
		

    </VCard>
	






    <div id="secondrop">
    </div>
	<div v-if="!$store.state.isAuthenticated">
		<div id="logg" v-if="lose">
			
			<h2 id="head" @click="loss">login</h2>
			<button id="heads" @click="loss">login</button>
			
		

		</div>
		<div v-if="!terms">
		<div id="logg" v-if="!lose">
			
			<h2 id="head" v-if="reggie">register</h2>
			
			<button id="heads" @click="loss">register</button>
			
			<h2 id="head" v-if="resetboys">reset</h2>
			
		

		</div>
		</div>
	</div>



    <div id="back">
		<img :src = "require('../assets/lord.png')" alt="unlimitedone" id="greenbeanss" v-if='!$store.state.isAuthenticated'/>
		
        <div id="greenbean"> <!--//turn off when namek login needed	-->	
			<div id="generator" v-if="$store.state.isAuthenticated">
				<label id="worldtitle">WORLD HUB</label>
			</div>
			<div id="generatorbottom"  v-if="$store.state.isAuthenticated"></div>
			
			<div id="loggedin"  v-if="$store.state.isAuthenticated">	
				<div id="logbuttons">
					<img :src = "require('../assets/loserssore.png')" alt="planet" id="planet" v-if="viewnormal"/>
					<div id="igbg" v-if="viewnormal">
							<div id="igbgbg"></div>
							<div id="igbgbgbg"></div>

							<div id="igbgbgbgbg"></div>
							<div id="igbgbgbgbgbg">
								<label id="Playertext">Welcome, \\{{username}}\\, ({{money}}$)</label>
							</div>
							
							<div>
								<button id="firstumg" class="umgone">umg(1)</button>
								<button id="secondumg" class="umgtwo" >umg(2)</button>
								<button id="thirdumg" class="umg">log-out</button>
								<button id="fourthumg" class="umg">rules</button>
								<label id="firstumgtag">Unlimited Money Glitch(1)</label>
								<label id="secondumgtag">Unlimited Money Glitch(2)</label>
							</div>
						</div>
				</div>
				<div id="logbuttons">
					<img :src = "require('../assets/loserssore.png')" alt="planet" id="planets" v-if="!viewnormal"/>


					<div id="ligbg" v-if="!viewnormal">
						<div id="ligbgbg"></div>
						<div id="ligbgbgbg"></div>

						<div id="ligbgbgbgbg"></div>
						<div id="ligbgbgbgbgbg">
							<label id="lPlayertext">Welcome, \\{{username}}\\, ({{money }}$)</label>
							
						</div>
						<div v-if="$store.state.isAuthenticated">
							<div>
								<button id="lfirstumg" class="umgone" v-if="gene">Generator</button>
								<button id="lsecondumg" class="umgtwo" v-if="gene">back</button>
							<div>
						</div>
						
							
						<div v-if="$store.state.isAuthenticated">
							<div v-if="vieworlds">
								<button id="lfirstumg" class="umgone" @click ='navigate'>Namek</button>
								<button id="lsecondumg" class="umgtwo">back</button>
							</div>
						</div>
						<label id="lfirstumgtag">Generator</label>
						
					</div>

					
					
					

					
				</div>
				

				
				<div id="entirebg"></div>
			</div>
		</div>
		</div>
		
			<img :src = "require('../assets/lord.png')" alt="unlimitedone" id="greenbeanss" v-if='!$store.state.isAuthenticated'/>
			<img :src = "require('../assets/lord.png')" alt="unlimitedone" id="greenbeans" v-if='!$store.state.isAuthenticated'/>
            
            <div id="playerdata">
            </div>


            <div id="inventory">
               
            </div>
            <div id="umgbar">
            </div>
            <div id="glitches">
          

            </div>


           



        </div>
        <VCard id="container">
            <div id="backdropone">

            </div>
			<div id="backdroptwo">
				
			</div>
			<div id="backdropforlist">
				<ul id="stupidul">
					<v-infinite-scroll height ='290' id="winnerscroll" >
					<li id='thatdumblist' v-for="lovers in WINLOGS">
						<VCardSubtitle id="wincoord">{{lovers.NAME}}(${{Intl.NumberFormat().format(lovers.AMOUNT)}})</VCardSubtitle>
						
					</li>
					</v-infinite-scroll>
				</ul>
			</div>
			<div id="backdropforlists"></div>
            <VCardSubtitle id="wintit">Win Log</VCardSubtitle>
			
        </VCard>

        <VCard id="disclaimer">"Unlimited Money Glitch, players will pay 1$ for a chance to win big."</VCard>


        <div id="stats">
            <label id="statscase">Unlimited Money Glitch</label>
        </div>

        <div id="content">
            <label id="contover"> Players will pay 1$ to enter queue for winning prize(XINF)</label>
        </div>
        <div id="actualback">

        </div>
    </div>
	<div v-if="$store.state.isAuthenticated">
		<div v-if="viewnormal">
		<button id="isover" class="firstumg"></button>
		<button id="isovertwo" class="secondumg" @click="gointogen"></button>
		<button id="isoverthree" class="threeumg" @click="Logout"></button>
		<button id="isoverfour" class="fourumg" ></button>
		</div>

		<div v-if="!viewnormal">
			<div v-if="gene">
			<button id="gen" class="genumg" v-if="gene" @click="gene = !gene"></button>
			<button id="genbackbutt" class="backumg" @click="lbackbutton"></button>
			</div>
			<div v-if="vieworlds">
			<button id="Namekbutt" class="namekumg" @click="genepush"></button>
			<button id="backbutt" class="backumg" @click="backbutton"></button>
			</div>
		
		</div>
	</div>
	<!--/<router-link to="/generator" id="isovertwo">Namekeee</router-link>--->

        <div id="chat">

        </div>

        <div id="money">
            <h1 id="love"></h1>
            <h1></h1>
        </div>








        


        <div id="cards">

        </div>
		<div v-if="!$store.state.isAuthenticated">
			<div v-if='wantshow'>
				<form id="form" @submit.prevent="logboy" v-if="lose">
					<div id="loginbox">
						<div id="backlogin">

						</div>

						<button id="uptop" type="button" @click="maker">REGISTER</button>

						<input id="username" v-model = "username" placeholder="username">

						

						<input id="password" type = 'password' v-model = 'password' placeholder="password">

						

						<div id="complete">

						</div>

						<button id="logtitle">LOGIN</button>
						<button id="forgotpasswordtitle" type="button" @click="disablelogres" v-if="forgotten">FORGOT PASSWORD</button>

						
					</div>
				</form>

				

				<form id="resetform" @submit.prevent="resetboy" v-if="resetboys">
					<div id="resetbox">
						<div id="backlogin">

						</div>

						<button id="uptop" type="button" @click="makerback">LOGIN</button>
						<label id="resetlabel">UNLIMITED MONEY GLITCH</label>
						<input id="Email" v-model = "emails" placeholder="email">

						

						

						

						<div id="complete">

						</div>

						<button id="logtitle">RESET</button>
						

						
					</div>

					
				</form>


				

				<ul id="lucid" v-if="lying == true">
					<li v-for="error in errors" id="li">
						<VCard @click = "close" id="Accountcreated">{{error}}</VCard>
					</li>
				</ul>

				

				<form id="form" @submit.prevent="regboy" v-if="!lose">
					<div id="registerbox" v-if="reggie">
						<div id="backlogin">

						</div>

						<button id="uptop" type="button" @click="maker">LOGIN</button>

						<input id="Name" v-model="name" placeholder="name">
						<input id="username" v-model = "username" placeholder="username">
						<input id="Email" v-model="email" placeholder="email">
						
							<div v-if="ageopen">
								<button id="buttonage" @click="ageopen = false ">x</button>
								<input id="age" type="text" v-model="age" placeholder="age">
							</div>
						

						<input id="password" type = 'password' v-model = 'password' placeholder="password">

						

						<div id="complete">

						</div>

						<button id="logtitle">REGISTER</button>

						<span class="dot"></span>

					</div>

					<div id = 'terms' v-if="terms">
						<VCard id="termsinfo">

							<VCardTitle id="ters">Terms and Conditions</VCardTitle>
							<v-infinite-scroll height = '340' id="scrollwheel">
							Please read these terms and conditions ("terms and conditions", "terms") carefully
							before using unlimitedmoneyglitch.com.
							<VCardSubtitle>Conditions of use</VCardSubtitle>
							By using this website, you certify that you have read and reviewed this Agreement and
							that you agree to comply with its terms. If you do not want to be bound by the terms of
							this Agreement, you are advised to stop using the website accordingly. Unlimited Money Glitch
							only grants use and access of this website, its products, and its services to those who
							have accepted its terms.
							<VCardSubtitle>Age restriction</VCardSubtitle>
							You must be at least 18 (eighteen) years of age before you can use this website. By
							using this website, you warrant that you are at least 18 years of age and you may
							legally adhere to this Agreement. Unlimited Money Glitch assumes no responsibility for
							liabilities related to age misrepresentation.
							<VCardSubtitle>Intellectual property</VCardSubtitle>
							You agree that all materials, products, and services provided on this website are the
							property of Unlimited Money Group, its affiliates, directors, officers, employees, agents,
							suppliers, or licensors including all copyrights, trade secrets, trademarks, patents, and
							other intellectual property. You also agree that you will not reproduce or redistribute Unlimited Money Group’s intellectual property in any way, including electronic, digital, or new
							trademark registrations.
							<VCardSubtitle>User accounts</VCardSubtitle>
							As a user of this website, you may be asked to register with us and provide private
							information. You are responsible for ensuring the accuracy of this information, and you
							are responsible for maintaining the safety and security of your identifying information.
							</v-infinite-scroll>
						</VCard>
						<VCard id="declineterms" @click="terms = !terms">Cancel</VCard>
						<VCard id="acceptterms" @click = 'regboy'>Accept</VCard>
					</div>
				</form>
				<ul id="lucid" v-if="successs">
					
					<div id="li"><VCard @click = "closesuc" id="Accountcreated">Account {{success}}</VCard></div>
					
					
				</ul>

				<ul id="lucid" v-if="lying == true">
					<li v-for="error in errors" id="li">
						<VCard @click = "close" id="Accountcreated">{{error}}</VCard>
					</li>
				</ul>
			</div>
		</div>
        

    </body>
    </html>
	
</template>

<script>
var x = 0
var y = 0
var teeths = false
var forgot = false
document.onmousemove = (ev) =>{
	//console.log(ev.target)

	x = ev.pageX
	y = ev.pageY
	//console.log(ev.target)
	if(ev.target.id == 'loginbox'){
		//console.log('forgot')
		forgot = true
	}else{
		forgot = false
	}

	if(ev.target.id == 'forgotpasswordtitle'){
		//console.log('forgot')
		forgot = true
	}

	if(ev.target.id == 'logtitle'){
		//console.log('forgot')
		forgot = true
	}

	if(ev.target.id == 'username'){
		//console.log('forgot')
		forgot = true
	}

	if(ev.target.id == 'password'){
		//console.log('forgot')
		forgot = true
	}
	
	
	if(false){

		
			document.getElementById("secondumgtag").style.left = x - 600 +'px'
			document.getElementById("secondumgtag").style.top = y - 1250 + 'px'

			document.getElementById("firstumgtag").style.left = x - 600 +'px'
			document.getElementById("firstumgtag").style.top = y - 1250 + 'px'
			if(ev.target.className == 'secondumg'){
				
				document.getElementById("secondumgtag").style.visibility = 'visible'
			}

			if(ev.target.className != 'secondumg'){
				
				document.getElementById("secondumgtag").style.visibility = 'hidden'
			}


			if(ev.target.className == 'firstumg'){
				
				document.getElementById("firstumgtag").style.visibility = 'visible'
			}

			if(ev.target.className != 'firstumg'){
				
				document.getElementById("firstumgtag").style.visibility = 'hidden'
			}
	
	}

	

}
import axios from 'axios'

export default{

	data(){
		return{
			errors:[],success:'',errorslength:0,lying:false,lose:true,teeth:false,gene:true,loggedin:false,successs:false,wantshow:false,username:'',money:0,
			vieworlds:false,viewgen:true,viewnormal:false, ageopen:false,status:false,WINLOGS:[],firstint:['"Unlimited Money Glitch" uses enhanced technology to assist all players in profiting.', 
			'"Unlimited Money Glitch" has odds in the world higher than any casino or betting platform.', 'For only $1(UM) players are able to place orders and win up to however much money is in queue.', '"Unlimited Money Glitch" does not profit off player losses or wins.',
			'Create an account at unlimitedmoneygroup.com/link your account, then transfer funds to Unlimited Money Glitch to get started.','Deposit at unlimitedmoneygroup.com.','Players vs Players.','Skill Based Market.','Do not share a key at any time, compromised keys will lead to funds being lost, keep your keys safe even after you redeem them.'
			], SOCIALS:['IG','TW','EM','YT'],forgotten:false,resetboys:false, reggie:true,terms:false, updateslog:['Revamped the login page - April 15, 2024','Increased the RTP/PTR from 99% to 99.9% - March 16, 2024'],
			allplayers:[],NUMUSERS:0
			
		}
	},

	mounted: async function() {		
		this.reload()
		setInterval(this.reload, 1000)
		this.GETSTATS()
		this.SETRIGHT()
		setInterval(this.GETSTATS,20000)
		setInterval(this.SETRIGHT, 200)
		setInterval(this.WINLOG, 5000)
		this.WINLOG()
		setInterval(this.Checks, 200)
		this.GETPLAYERS()
		setInterval(this.GETPLAYERS, 12000)
		
		

		
	},

	methods:{

		GOWINDOWS(){
			window.location.replace('https://unlimitedmoneygroup.com')
		},
		GETPLAYERS(){
			

				axios
					.get('/api/v1/playersplace').then(response =>{
						
						
						this.NUMUSERS = response.data.length
						this.allplayers = []
						if (response.data.length > 300){
							for (let i = 0; i < 300; i++){
											
									this.allplayers.push(response.data[i])
																								
																								
															}
						}else{
							this.allplayers = response.data
						}

						console.log(this.allplayers.length)
						//console.log(response.data)
						
						//console.log(response.data)

					}).catch(error => {
						if(error.response){
							this.successs = true
							this.success = error.response.data.email
							//console.log(error.response.data)
							
							
							
						}
					})
		},
		disablelogres(){
			this.resetboys = true
			this.reggie = false
			this.lose = false
		},

		resetboy(){
			const fromData = {
					email:this.emails
				}

				axios
					.post('/api/v1/users/reset_password/', fromData).then(response =>{
						

						this.successs = true
						this.success = 'Successfully sent, you will receive an email if it is associated with an account.'
						//console.log(response.data)

					}).catch(error => {
						if(error.response){
							this.successs = true
							this.success = error.response.data.email
							var self = this;
							
							setTimeout(function() {
								self.successs = false;
								
							}, 1500);
							//console.log(error.response.data)
							
							
							
						}
					})
		},
		Checks(){
			if(forgot == true){
				//console.log(this.forgotten)
				this.forgotten = true
			}else{
				this.forgotten = false
			}
		},
		WINLOG(){
			axios
					.get('/api/v1/WINLOGS/').then(response =>{
						this.WINLOGS = response.data
						
							for (let i = 0; i < this.WINLOGS.length; i++){
											
								this.WINLOGS[i].DATE = this.WINLOGS[i].DATE.split('T')[0]
								this.WINLOGS[i].AMOUNT = this.WINLOGS[i].AMOUNT.toFixed(2)			
																					
																					
												}
						
						
						//console.log(response.data, 'stupidjava')

						

					}).catch(error => {
						if(error.response){
							
							//console.log(error.response.data)
							
							
							
						}
					})
		},
		reload(){
			this.status = localStorage.GOINGBACK
			//console.log(this.status,'idiot')
			if(this.$store.state.isAuthenticated){

			
				if(localStorage.GOINGBACK){
					//console.log('iwin')
					window.location.reload()
					localStorage.removeItem('GOINGBACK')
				}
			}

			if(!this.$store.state.isAuthenticated){

			
				if(localStorage.GOINGBACK){
					//console.log('iwin')
					window.location.reload()
					localStorage.removeItem('GOINGBACK')
				}
			}
			
					
					
				
				
			

		},
		

		genepush(){
			this.$router.push('generator')
		},

		gointogen(){
			this.viewnormal = false
			this.vieworlds = false
			this.gene = true
		},

		async SETRIGHT(){
			if(this.gene == true){
				this.vieworlds = false
			}else{
				this.vieworlds = true
			}

			if(this.viewnormal == true){
				teeths = true
			}else{
				teeths = false	
			}

			if(this.$store.state.isAuthenticated == false){
				teeths = false
			}

		
			

			
		},


		backbutton(){
			this.gene = true
			this.vieworlds = false
		},

		lbackbutton(){
			this.gene = false
			this.vieworlds = false
			this.viewnormal = true
		},



		GETSTATS(){
				if(this.$store.state.token){

				
				const fromData = {
					'Token':this.$store.state.token
				}

				axios
					.post('/api/v1/playerpost/', fromData).then(response =>{
						
						//console.log(response.data)

						

						this.username = response.data.username.toUpperCase()
						this.money = Intl.NumberFormat().format(response.data.UM)
						//console.log(this.username)

					}).catch(error => {
						if(error.response){
							
							//console.log(error.response.data)
							
							
							
						}
					})
				}
			
		},
		loss(){
			this.wantshow = !this.wantshow
		},
		close(){
			//console.log('yayo')
			this.errors = []
			this.lying = false
		},

		closesuc(){
			
			this.successs = false
			this.success = ''
			this.password = ''
		},


		maker(){

			this.lose = !this.lose
		},

		makerback(){
			this.resetboys = false
			this.lose = true
			this.reggie = true
		},

		regboy(){
			if(this.ageopen == true){

				if(this.terms == false){
					this.terms = true
				}else{

				
				


					if (!this.errors.length){
						const fromData = {
							username: this.username,
							password: this.password,
							email: this.email,
							name:this.name,
							Age:this.age
						}

						axios
							.post('/api/v1/users/', fromData).then(response =>{
								//console.log(response)
								this.success = response.statusText
								this.successs = true
								this.terms = false
								//console.log(response.statusText)
								this.lose = true




							}).catch(error => {
								if(error.response){
									this.errors = error.response.data
									//console.log(error.response.data)
									this.lying = true
									this.terms = false
									var self = this;
							
									setTimeout(function() {
										self.lying = false;
										
									}, 2500);
									
									
									
								}
							})
					}
			}
			}else{
				this.ageopen = true
			}
		},

		async logboy(){
			axios.defaults.headers.common['Authorization'] = ''
			localStorage.removeItem('token')
				const fromData = {
					username: this.username,
					password: this.password,
					
					
				}

				axios
					.post('/api/v1/token/login/', fromData).then(response =>{
						const token = response.data.auth_token

						this.$store.commit('setToken', token)
						
						axios.defaults.headers.common['Authorization'] = 'Token '+ token

						localStorage.setItem('token', token)
						
						//console.log(response.data)
						this.success = "Successfully logged in"
						this.GETSTATS()
						this.successs = true
						var self = this;
						this.password = ''
						setTimeout(function() {
							self.loggedin = true;
							self.$router.push({path:'/generator'})
						}, 2500);

						this.gohead()
						

						//this.gohead()
						
						//document.getElementById("form").style.visibility = "hidden"
						//document.getElementById("formcred").style.visibility = "hidden"

					}).catch(error => {
						if(error.response){
							//console.log(error.response.data)
							this.lying = true
							this.errors = error.response.data
							this.password = ''

							var self = this;
							
							setTimeout(function() {
								self.lying = false;
								
							}, 1500);
						}
				})
				
				
					
					
			},

			async Logout(){

				axios
					.post('/api/v1/token/logout/')
					.then(response =>{
						
						
						//console.log('Logged Out')
					
					}).catch(error => {
						if(error.response){
							//console.log(error.response.data)
						}
					})
				axios.defaults.headers.common['Authorization'] = ''
				localStorage.removeItem('token')
				localStorage.removeItem('token')
				this.$store.commit('removeToken')
				localStorage.removeItem('username')
				localStorage.removeItem('id')
				this.password = ''
				teeths = false



	
			},


			async gohead(){

				axios
					.get('/api/v1/users/me').then(response =>{
						
						this.username = response.data.username
						
						


						this.$store.commit('setUser', {'id':response.data.id, 'username':response.data.username})

						localStorage.setItem('username', response.data.username)
						localStorage.setItem('id', response.data.id)

						//console.log(this.$store.state.user)
						
						document.getElementById("form").style.visibility = "hidden"
						document.getElementById("formcred").style.visibility = "hidden"

					}).catch(error => {
						if(error.response){
							//console.log(error.response.data)
						}
				})
			},


	}




}

</script>

<style scoped>
#body {
            background-color: grey;
        }

h1 {
            color: whitesmoke;
        }

p {
            color: red;
        }
#mikevic{
	scrollbar-width: none;
  -ms-overflow-style: none;
}

#withdrawdepo{
	position: absolute;
	width:16.4%;
	z-index: 20;
	height:5%;
	left:37.5%;
	top:84.5%;
	color:rgba(0, 0, 0, 0.283);
}

#ters{
	background-color: rgb(170, 170, 170);
}
#textappear {
	margin-top:4%;
	left:6.5%;
	margin-left: -2%;
	position: relative;
	color:rgb(13, 143, 58);
	

	
}
#apper{
	scrollbar-width: none;
  -ms-overflow-style: none;
}
#appear{
	
	width:85%;
	height:140%;
	font-size: 200%;
	border:2px solid rgb(0, 39, 0);
	background-color: rgb(0, 38, 12);
}
#sp{
	
	font-size: 40%;
	margin-top:0%;
}
#winnerscroll{
	scrollbar-width: none;
  -ms-overflow-style: none;
  color:rgb(11, 18, 11);
}
#acceptterms{
	width:30%;
	height:6.5%;
	top:87.5%;
	font-size: 115%;
	right:2.5%;
	text-align: center;
	color:rgb(3, 58, 3);
	border:2px solid rgb(5, 54, 5);
	position: absolute;
	background-color: rgb(7, 122, 51);
}

#declineterms{
	width:25%;
	height:6.5%;
	top:87.5%;
	font-size: 115%;
	right:35%;
	text-align: center;
	color:rgb(77, 77, 77);
	border:2px solid rgb(53, 53, 53);
	position: absolute;
	background-color: rgb(146, 146, 146);
}
#inter {
	color:rgb(3, 203, 73);
	background-color: rgb(4, 4, 4);
	border: 2px solid rgb(15, 15, 15);
	width:96%;
	font-weight: 500;
	right:-2%;
	top:10%;
	letter-spacing: 2px;
	margin-top:0.01%;
	filter:drop-shadow(2px 2px 2px black)
	
}

#firstintrocontent{
	background-color: rgba(6, 120, 16, 0.409);
}

#firstintrocontents{
	position: absolute;
	width:100%;
	height:100%;
	top:0%;
	pointer-events: none;
	opacity: 0.7;
	background-color: rgb(0, 0, 0);
}

#interl{
	position: absolute;
	width: 100%;
	color:rgb(149, 229, 149);
	text-align: center;
}
#screenshot{
	position:absolute;
	width:99%;
	height:99%;
	right:0.5%;
	opacity:0.7;
}

#screenshottwo{
	position:absolute;
	width:110%;
	height:98%;
	right:-4.5%;
}
#name {
	position: absolute;
	width: 100%;
	height: 0px;
	padding: 10px;
	margin: 40;
	right:0.25%;
	top: 104.5%;
	text-align: center;
	z-index: 3;
	font-size:80%;
	font-weight:400;
	opacity:0.1;
	font-family:'Arial Narrow';
	color:rgb(0, 0, 0);
	letter-spacing:5px;
}


#abs {
	position: absolute;
	z-index: 10;
	top: 300%;
	right:50%;
	background-color: black;
	opacity: 0.5;
	filter: drop-shadow(0px 4px 8px #222d33);
}


#droppedclass {
	width: 98%;
	height: 90%;
	right: 1%;
	top: 19%;
	position: absolute;
	z-index: 20;
}

#dropclass {
	opacity:0;
	width: 97%;
	height: 97%;
	right: 0%;
	top: 0%;
	pointer-events: none;
	position: absolute;
	z-index: 10;
}

#firstdrop {
	pointer-events: none;
	opacity: 0.5;
	width: 100%;
	height: 100%;
	right: 0%;
	top: 0%;
	background-color: black;
	opacity: 0.5;
	position: absolute;
	z-index: 15;
	border: 3px solid rgb(92, 92, 92);
	filter: drop-shadow(2px 2px 2px #222d33);
}

#god {
	position: absolute;
	right: 33.5%;
	top: 90%;
	width: 400px;
	z-index:15;
	visibility:hidden;
	background-color:red;

}

#loginbut {
	color:green;
	background-color:lightgreen;
}

#index {
	color: green;
	background-color: lightgreen;
}

#AboutUs {
	color: green;
	background-color: lightgreen;
}

#Glitches {
	color: green;
	background-color: lightgreen;
}

#Rules {
	color: green;
	background-color: lightgreen;
}

#Pros {
	color: green;
	background-color: lightgreen;
}

#loginbox{
	width:20%;
	height:30%;
	top:180%;
	right:40%;
	position: absolute;
	z-index: 10;
	visibility: visible;
	background-color: rgb(24, 24, 24);
}


#resetbox{
	width:20%;
	height:30%;
	top:180%;
	right:40%;
	position: absolute;
	z-index: 10;
	visibility: visible;
	background-color: rgb(24, 24, 24);
}


#terms {
	width:30%;
	height:72.5%;
	top:160%;
	right:35%;
	position: absolute;
	z-index: 25;
	border:2px solid rgb(33, 33, 33);
	visibility: visible;
	background-color: rgb(18, 18, 18);
}
#scrollwheel{
	padding:5px;
	text-align: center;
}
#termsinfo {
	width:90%;
	height:72.5%;
	top:5%;
	right:5%;
	position: absolute;
	z-index: 25;
	color:rgb(18, 18, 18);
	border:1px solid rgb(123, 123, 123);
	visibility: visible;
	background-color: rgb(173, 173, 173);
}
#registerbox{
	width:20%;
	height:30%;
	top:180%;
	right:40%;
	position: absolute;
	z-index: 10;
	visibility: visible;
	background-color: rgb(24, 24, 24);
}

#Accountcreated{
	top:190%;
	width: fit-content;
	
	z-index: 10;
	height:6%;
	opacity: 0.8;
	letter-spacing: 2px;
	text-align: center;
	color:rgb(26, 26, 26);
	font-family: 'Arial Narrow';
	border:2px solid rgb(49, 49, 49);
	position: relative;
	background-color: rgb(65, 155, 65);
}
#uptop{
	width: 40%;
	height:22.5%;
	right:-22.5%;	
	top:152.5%;
	opacity: 0.3;
	font-family: 'Arial Narrow';
	position: absolute;
	color:rgb(177, 177, 177);
	text-align: center;
	background-color: #222d33;
	
}

#logtitle{
	position: absolute;
	width:100%;
	color:green;
	text-align: center;
	top:80%;
	font-family: 'Arial Narrow';
	letter-spacing: 2px;
}

#forgotpasswordtitle{
	position: absolute;
	width:100%;
	color:rgb(104, 104, 104);
	text-align: center;
	top:65%;
	font-family: 'Arial Narrow';
	letter-spacing: 2px;
	
	
}



#lucid{
	list-style:none;
	width:20%;
	height:30%;
	top:180%;
	right:40%;
	position: absolute;
	z-index: 11;
	display: flex;
  	align-items: center;
  	justify-content: center;
}

#username{
	position: absolute;
	background-color: rgb(3, 3, 3);
	top:30%;
	right:12.5%;
	width: 75%;
	opacity: 0.7;
	height:12.5%;
	border:2px solid rgb(46, 46, 46);
	text-align: center;
	color:white;
}

#Name{
	position: absolute;
	background-color: rgb(3, 3, 3);
	top:15%;
	right:12.5%;
	width: 75%;
	opacity: 0.7;
	height:12.5%;
	border:2px solid rgb(46, 46, 46);
	text-align: center;
	color:white;
}


#Email{
	top:60%;
	right:12.5%;
	height:12.5%;
	width: 75%;
	border:2px solid rgb(46, 46, 46);
	position: absolute;
	opacity: 0.7;
	background-color: rgb(3, 3, 3);
	text-align: center;
	color:white;
}

#resetlabel{
	width:100%;
	height:50%;
	top:10%;
	font-family:'arial narrow';
	color:rgb(164, 164, 164);
	font-size:200%;
	letter-spacing:2px;
	opacity:0.8;
	text-align:center;
	position:absolute;

}
#password{
	top:45%;
	right:12.5%;
	height:12.5%;
	width: 75%;
	border:2px solid rgb(46, 46, 46);
	position: absolute;
	opacity: 0.7;
	background-color: rgb(3, 3, 3);
	text-align: center;
	color:rgb(133, 133, 133);
}

#intro {
	position: absolute;
	z-index: 10;
	top: 15%;
	right: 4.50%;
	height: 70%;
	width: 50%;
	filter: drop-shadow(0px 4px 8px #222d33);
	z-index: 20;
}

#buttonage{
	position:absolute;
	right:14%;
	top:29%;
	z-index:21;
	color:green;
	font-size:50%;
}

#age{
	position: absolute;
	
	top:35%;
	right:15%;
	width: 70%;
	opacity: 0.8;
	height:17.5%;
	border:2px solid rgb(42, 135, 19);
	text-align: center;
	font-size:200%;
	z-index:20;
	font-family:'arial narrow';	
	color:rgb(28, 140, 61);
	background-color:rgb(18, 84, 18);
}
#firstintro {
	position: absolute;
	z-index: 15;
	top: -15%;
	margin: auto;
	padding:0.2%;
	width: 30%;
	left:-3%;
	height: 97.5%;
	opacity:0.6;
	border:2px solid rgb(39, 39, 39);
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(4px 4px 8px #222d33);
}

#firstintrosocial{
	width: 20%;
	position:absolute;
	height:10%;
	left:1.75%;
	top:90%;
	background-color: rgb(16, 16, 16);
	border:2px solid rgb(50, 50, 50);
	filter: drop-shadow(0px 4px 4px #222d33);
}

#socials{
	position:absolute;
	width: 80%;
	height:90%;
	top:5%;
	right:10%;
	background-color: rgb(80, 80, 80);
	
}

#joebelow{
	display:inline-block;
	list-style:none;
	margin-right:12%;
	margin-top:-0.5%;
	
}

#buttonbelow{
	width:200%;	
	left:40%;
	line-height:230%;
	position:relative;
	background-color:rgb(53, 53, 53);
	border:2px solid rgb(78, 78, 78);
	color:rgb(150, 150, 150);
	opacity:0.8;	
	
}

#firstintrobg{
	width:98%;
	height:92%;
	right:1%;
	top:1%;
	opacity:0.8;
	position:absolute;
	background-color:rgb(12, 12, 12);

}

#firstintli{
	list-style:none;
	font-family:'arial narrow';
	color:rgb(2, 85, 2);
	text-align:center;
	margin-bottom:2%;
	letter-spacing:2px;
	font-size:100%;
}
#iframecapture{
	position:absolute;
	width:70.50%;
	height:70%;
	border: 2px solid rgb(74, 74, 74);
	right:-3.6%;
	top:-4%;
	background-color: rgb(109, 109, 109);
}
#uppy{
	text-align: left;
	color:rgb(6, 59, 6);
}
#capturetitle{
	position:absolute;
	width:99.5%;
	height:7.5%;
	border-bottom: 2px solid rgb(47, 47, 47);
	right:.25%;
	top:1%;
	letter-spacing: 2px;
	font-weight:400;
	font-size: 90%;
	color: rgb(255, 255, 255);
	background-color: rgb(109, 109, 109);
}

#capturetitles{
	position:absolute;
	width:94.25%;
	height:4.5%;
	right:5.175%;
	top:94.6%;
	letter-spacing: 2px;
	color: rgb(255, 255, 255);
	background-color: rgb(206, 206, 206);
}

#Moneyavs{
	position:absolute;
	width:12.25%;
	height:21.5%;
	right:1.175%;
	border:2px solid rgb(0, 53, 10);
	top:76%;
	letter-spacing: 2px;
	color: rgb(255, 255, 255);
	background-color: rgb(5, 31, 1);
}
#capturebackground{
	position:absolute;
	width:55%;
	height:85.5%;
	
	right:43%;
	text-align: center;
	font-size: 110%;
	top:11%;
	
	color: rgb(255, 255, 255);
	background-color: rgb(7, 114, 29);
}

#Validation{
	position:absolute;
	width:42.5%;
	height:65.5%;

	right:3%;
	text-align: center;
	font-size: 110%;
	top:15%;
	color: rgb(255, 255, 255);
	background-color: rgb(7, 114, 29);
}

#deadwrong {
	text-align: right;
	color:rgb(0, 172, 49);
}

#deadwrongstare{
	background-color:rgba(0, 37, 6, 0.357);
	position: absolute;
	width:100%;
	top:12.5%;
	height:80%;
}
#ValidationEager{
	position:absolute;
	width:51%;
	height:84.5%;
	right:48%;
	z-index: 20;
	text-align: center;
	font-size: 110%;
	top:11%;
	color: rgb(255, 255, 255);
	background-color: rgb(1, 22, 6);
}

#carl{
	
	border:2px solid rgb(7, 22, 0);
	font-size: 50%;
	background-color: rgb(7, 49, 5);
}

#vali{
	position: absolute;
	font-size: 100%;
	width:100%;
	top:84%;
	right:1%;
	text-align: right;
	color:rgb(166, 238, 176);
}
#inst{
	padding:2px;
}
#carlugly{
	width: 95%;
	right:2.5%;
	height:7.5%;
	top:85%;
	color: green;
	padding:5px;
	font-size: 80%;
	text-align: center;
	position: absolute;
	background-color: rgb(0, 0, 0);
}

#carluglyson{
	width: 100%;
	right:2.5%;
	height:7.5%;
	top:92.5%;
	color: green;
	padding:5px;
	font-size: 60%;
	letter-spacing: 1px;
	text-align: center;
	position: absolute;
}
#capturebackgroundreal{
	position:absolute;
	width:55%;
	height:85.5%;
	pointer-events: none;
	right:43%;
	text-align: center;
	font-size: 110%;
	top:11%;
	
}
#capturebackgroundsolvent{
	position:absolute;
	width:50%;
	height:10%;
	right:1%;
	text-align: center;
	font-size: 110%;
	top:2%;
	border:2px solid green;
	color: rgb(39, 39, 39);
	background-color: rgb(19, 200, 58);
}

#capturebackgroundsolvents{
	position:absolute;
	width:40%;
	height:10%;
	right:4.5%;
	text-align: center;
	font-size: 110%;
	z-index: 50;
	top:83.5%;
	border:2px solid rgb(2, 43, 2);
	color: rgb(39, 39, 39);
	background-color: rgb(4, 57, 16);
}
#capturebackgroundsolventss{
	position:absolute;
	width:10%;;
	height:100%;
	text-align: center;
	font-size: 110%;
	top:0%;
	border:2px solid rgb(2, 43, 2);
	color: rgb(39, 39, 39);
	background-color: rgb(2, 26, 4);
}

#depositbutton{
	width:75.5%;
	right:2.5%;
	height:65.5%;
	top:20%;
	font-size:80%;
	color:black;
	border:2px solid rgb(5, 48, 5);
	position: absolute;
	background-color: rgb(11, 63, 33);
}

#movedeposit{
	letter-spacing: 1px;
	margin-top:2%;
}

#captitle{
	width:100%;
	right:0%;
	top:25%;

	font-size: 80%;
	position: absolute;
}

#surname{
	width:100%;
	top:95%;
	height:5%;
	background-color: rgb(1, 32, 0);
	position: absolute;
}
#capturebackgroundsolution{
	position:absolute;
	width:38%;
	height:57.5%;
	border: 2px solid black;
	right:1.30%;
	text-align: center;
	font-size: 110%;
	top:10%;
	opacity: 0.8;
	color: rgb(255, 255, 255);
	background-color: rgb(10, 74, 13);
}

#capturebackgroundsolutiondata{
	position:absolute;
	width:38%;
	height:17.5%;
	border-left: 2px solid black;
	border-right: 2px solid black;
	right:1.30%;
	text-align: center;
	font-size: 110%;
	top:38%;
	opacity: 1;
	color: rgb(255, 255, 255);
	background-color: rgb(18, 81, 21);
}

#capturebackgroundsolutionpresentdata{
	position:absolute;
	width:58%;
	height:10.5%;

	right:0.5%;
	text-align: center;
	font-size: 110%;
	top:70.5%;
	border:2px solid rgb(129, 129, 129);
	opacity: 0.8;
	color: rgb(255, 255, 255);
	background-color: rgb(8, 8, 8);
}
#capturebackgrounds{
	position:absolute;
	width:56.5%;
	height:87.5%;

	right:42%;
	text-align: center;
	pointer-events: none;
	font-size: 110%;
	top:10%;
	color: rgb(255, 255, 255);
	background-color: rgb(26, 26, 26);
}
#capturebackgroundsolve{
	position:absolute;
	width:100%;
	height:1%;
	right:0%;
	text-align: center;
	font-size: 110%;
	top:99%;
	color: rgb(255, 255, 255);
	background-color: rgb(8, 47, 17);
}
#capturebackgroundselve{
	position:absolute;
	width:100%;
	height:87%;
	right:0%;
	text-align: center;
	font-size: 110%;
	pointer-events: none;
	top:10%;
	color: rgb(255, 255, 255);
	background-color: rgb(8, 47, 17);
}

#iframe{
	position:absolute;
	width:65.2%;
	height:60%;
	right:-1.75%;
	top:0%;
}

#secondintro {
	position: absolute;
	z-index: 14;
	top: -17%;
	right: 37%;
	padding: 0.2%;
	width: 28%;
	height: 135%;
	border:4px solid rgb(18, 18, 18);
	opacity: 1;
	
}

#secondintrobg{
	
	position: absolute;
	width:100%;
	height:100%;
	right:0%;
	top:0%;
	opacity:0.8;
	background-color: rgb(16, 16, 16);
}
#secondintrobgbgbg{
	position: absolute;
	width:103%;
	height:102%;
	left:-1.5%;
	top:-1%;
	background-color:transparent;
	border:2px solid rgb(31, 31, 31);
}

#secondintrobgbgbgbg{
	position: absolute;
	z-index: 14;
	top: -18.5%;
	right: 33.5%;
	padding: 0.2%;
	width: 35%;
	height: 138.25%;
	opacity: 0.1;
	background-color:rgb(30, 30, 30)
}

#secondintrobgbg{
	
	position: absolute;
	width:100%;
	height:50%;
	right:0%;
	border-top: 4px solid   rgb(12, 12, 12);
	border-bottom: 4px solid   rgb(12, 12, 12);
	top:25%;
	opacity:0.8;
	background-color: rgb(11, 11, 11);
}


#thirdintro {
	position: absolute;
	z-index: 15;
	top: 0%;
	padding: 0.2%;
	
	width: 35%;
	margin: auto;
	right:-2.5%;
	height: 100%;
	opacity: 1;
	border:2px solid rgb(60, 60, 60);
	
}



#firstin {
	position: absolute;
	z-index: 10;
	top: 10%;
	right: 10%;
	background-color: black;
	opacity: 1;
	filter: drop-shadow(0px 4px 8px #222d33);
}






#backdropone {
	position: absolute;
	width: 100%;
	height: 100%;
	
	padding: 10px;
	border: 0px solid gray;

	right: 0px;
	top: 0px;
	background-color: rgb(0, 0, 0);
	z-index:3;
	opacity: 0.7;
	filter: drop-shadow(0px 4px 4px #222d33);
}

#backdroptwo{
	width:98%;
	height:84%;
	position: absolute;
	background-color: rgb(19, 19, 19);
	right:1%;
	top:15%;
	opacity: 0.2;
	z-index: 4;
}



#backdropforlist{
	width:98%;
	height:84%;
	position: absolute;
	background-color: rgb(0, 0, 0);
	right:1%;
	top:15%;
	opacity: 0.2;
	z-index: 4;
}

#backdropforlists{
	width:98%;
	height:84%;
	position: absolute;
	background-color: rgba(0, 19, 1, 0.557);
	right:1%;
	top:15%;
	opacity: 0.2;
	pointer-events: none;
	z-index: 4;
}

#wincoord{
	position: relative;
	width:100%;	
	height: 100%;
	z-index: 6;
	top:0%;
	letter-spacing: 1px;
	font-size: 100%;
	filter:drop-shadow(0px 0px 2px rgba(0, 0, 0, 0.31));
	right: 0%;
	color:rgb(37, 218, 91);
}

#thatdumblist{
	text-align: center;
	color:green;
	position: relative;
	margin:1% 0;
	margin-top:0%;
	
}

#stupidul{
	top:5%;
	width: 100%;
	text-align: center;
	position: absolute;
	list-style: none;
	
}



#container {
	width: 17.25%;
	height: 51.5%;
	padding: 10px;
	border: 0px solid gray;
	right: 75%;
	top: 22.5%;
	position: absolute;
	z-index: 16;
	background-color:rgb(28, 28, 28);
}
#wintit {
	position: absolute;
	width: 100%;
	height: 10%;
	padding: 10px;
	right: 0%;
	top: 3%;
	z-index: 13;
	text-align:center;
	color:rgb(3, 62, 7);	
	font-weight: 600;
	font-size: 102.5%;
	filter:brightness(1.5);
}
#entryone {
	position: absolute;
	z-index: 10;
	top: 160px;
}


#headerone {
	position:absolute;
	top: 0px;
}
#enterone {
	position: absolute;
	z-index: 9;
	top: 260px;
}





#winning {
	position: absolute;
	width: 85%;
	height: 4%;
	padding: 10px;
	right: 7%;
	top: 18%;
	background-color:seagreen;
	opacity: 1;
	z-index: 20;
	filter: drop-shadow(0px 4px 4px #222d33);
	text-align: center;
	color:lightgreen;
}

#secondrop {
	background-color: black;
	opacity: 0.5;
	margin: 40;
	width: 95%;
	height: 125%;
	right: 2%;
	top: 270%;
	background-color: black;
	opacity: 0.5;
}


#divvy {
	position: absolute;
	width: 100%; 
	height: 12.5%;
	padding: 10px;
	margin: 40;
	right: 0px;
	right: 0px;
	top: 0px;
	background-color: rgb(151, 151, 151);
	opacity: 1;
	filter: drop-shadow(2px 2px 2px #6e6e6e)
}


#threediv{
	position: absolute;
	width: 100%; 
	height: 252%;
	padding: 10px;
	pointer-events: none;
	margin: 40;
	right: 0px;
	right: 0px;
	top: 0px;
	background-color: grey;
	opacity: 1;
	filter: drop-shadow(2px 2px 2px #6e6e6e)
}



#absolute {
	position: absolute;
	width: 90px;
	height: 430px;
	padding: 10px;
	border: 2px;
	border-style: outset;
	border-color: #66ff66;
	margin: 40;
	right: 28%;
	top: 302.5%;
	background-color: black;
	opacity: 0.5;
	filter: drop-shadow(0px 4px 4px #222d33);
}







#logg {
	position: absolute;
	width: 10.75%;  
	height: 1%;
	padding: 10px;
	border: 2px solid rgb(96, 96, 96);
	margin: 40;
	right: 55%;
	top: 220%;
	transform: rotate(90deg);
	background-color: palegreen;
	z-index: 1000;
	opacity: 0.9;
	filter:brightness(1.2);
	font-size: 75%;
	font-family: Helvetica;
	filter:contrast(1.3);
	filter: drop-shadow(2px 4px 4px #222d33);
	
	
}

#greenbean {
	position: absolute;
	width: 34.65%;
	height: 85%;
	padding: 10px;
	border: 2px solid rgb(48, 48, 48); 
	margin: 40;
	right: 33.35%;
	top: 5.5%;
	background-color: black;
	opacity: 1;
	z-index: 2;
	filter: drop-shadow(0px 4px 4px #222d33);
	
}

#planet{
	right:-17.7%;
	z-index: 1;
	width: 130%;
	height: 100%;
	opacity: 0.5;
	z-index: 3;
	filter: brightness(0.65);
	position: absolute;
}

#planets{
	right:-17.7%;
	z-index: 1;
	width: 130%;
	height: 100%;
	opacity: 0.5;
	z-index: 3;
	filter: brightness(0.65);
	position: absolute;
}


#igbg{
	width:100%;
	right:0%;
	top:1%;
	border: 2px solid rgb(47, 47, 47);
	position: absolute;
	height: 100%;
	z-index: 14;
	

	
}


#ligbg{
	width:100%;
	right:0%;
	top:1%;
	border: 2px solid rgb(47, 47, 47);
	position: absolute;
	height: 100%;
	z-index: 10;

	
}


#generator{
	width: 100%;
	height: 10%;
	top:10%;
	background-color: rgb(19, 19, 19);
	text-align: center;
	color: GREEN;
	border:2px solid rgb(41, 41, 41);
	font-family: 'Arial Narrow';
	
}

#worldtitle{
	width: 100%;
	height: 10%;
	right: 0%;	
	top:4.5%;
	position: absolute;
	text-align: center;
	color: green;
	z-index: 5;
	
	letter-spacing: 1px;
	font-family: 'Arial Narrow';
	
}



#generatorbottom{
	width: 99%;
	height: 7.5%;
	top:92%;
	right: .5%;
	opacity: 0.4;
	z-index: 5;
	position: absolute;
	background-color: rgb(97, 97, 97);
}

#igbgbg{
	width:100%;
	height: 100%;
	top:0%;
	right: 0%;
	position: absolute;
	opacity: 0.3;
	background-color: rgb(49, 49, 49);
	filter: drop-shadow(4px 4px 4px #2a332e);
	
}


#ligbgbg{
	width:100%;
	height: 100%;
	top:0%;
	right: 0%;
	position: absolute;
	opacity: 0.3;
	background-color: rgb(49, 49, 49);
	filter: drop-shadow(4px 4px 4px #2a332e);
	
	
}

#igbgbgbg{
	width:100%;
	height: 100%;
	top:0%;
	right: 0%;
	position: absolute;
	opacity: 0.3;
	background-color: rgb(49, 49, 49);
	filter: drop-shadow(4px 4px 4px #2a332e);
	
}


#ligbgbgbg{
	width:100%;
	height: 100%;
	top:0%;
	right: 0%;
	position: absolute;
	opacity: 0.3;
	background-color: rgb(49, 49, 49);
	filter: drop-shadow(4px 4px 4px #2a332e);
	
}

#igbgbgbgbg{
	width:98%;
	height: 98%;
	top:1%;
	right: 1%;
	position: absolute;
	opacity: 0.3;
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(4px 4px 4px #2a332e);
}


#ligbgbgbgbg{
	width:98%;
	height: 98%;
	top:1%;
	right: 1%;
	position: absolute;
	opacity: 0.3;
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(4px 4px 4px #2a332e);
}

#igbgbgbgbgbg{
	width:97%;
	height: 12.5%;
	top:82.5%;
	right: 1.5%;
	color:rgb(0, 255, 0);
	position: absolute;
	opacity: 0.3;
	background-color: rgb(0, 0, 0);
	font-family: 'Arial Narrow';
	text-align: center;
	font-weight: bold;

}


#ligbgbgbgbgbg{
	width:97%;
	height: 12.5%;
	top:82.5%;
	right: 1.5%;
	color:rgb(0, 255, 0);
	position: absolute;
	opacity: 0.3;
	background-color: rgb(0, 0, 0);
	font-family: 'Arial Narrow';
	text-align: center;
	font-weight: bold;

}

#Playertext{
	width: 100%;
	top:25%;
	right:0%;
	position: absolute;
	font-family:'arial narrow';
	letter-spacing:2px;
	text-transform:uppercase;
	font-weight:100;
}
#lPlayertext{
	width: 100%;
	top:25%;
	right:0%;
	position: absolute;
	font-family:'arial narrow';
	letter-spacing:2px;
	text-transform:uppercase;
	font-weight:100;
}
#firstumg{
	width:18.5%;
	height: 18%;
	border: 2px solid rgb(41, 41, 41);
	margin: 12.5% 7%;
	color:green;
	position: absolute;
	letter-spacing: 1px;
	font-family: 'Arial Narrow';
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(2px 4px 4px #000000);
}

#lfirstumg{
	width:18.5%;
	height: 18%;
	border: 2px solid rgb(41, 41, 41);
	margin: 12.5% 7%;
	color:green;
	position: absolute;
	letter-spacing: 1px;
	font-family: 'Arial Narrow';
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(2px 4px 4px #000000);
}

#lsecondumg{
	width:18.5%;
	height: 18%;
	z-index: 4;
	letter-spacing: 1px;
	border: 2px solid rgb(41, 41, 41);
	margin: 12.5% 29%;
	color:green;
	font-family: 'Arial Narrow';
	position: absolute;
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(2px 4px 4px #000000);
}
.dot{
	height: 4.5%;
	width: 3%;
  	background-color: #838383;
  	border-radius: 50%;
	right:1.5%;
	top:2%;
	position: absolute;
  	display: inline-block;
	visibility: hidden;
}

#secondumg{
	width:18.5%;
	height: 18%;
	z-index: 4;
	letter-spacing: 1px;
	border: 2px solid rgb(41, 41, 41);
	margin: 12.5% 29%;
	color:green;
	font-family: 'Arial Narrow';
	position: absolute;
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(2px 4px 4px #000000);
}

#thirdumg{
	width:18.5%;
	height: 18%;
	z-index: 4;
	letter-spacing: 1px;
	border: 2px solid rgb(41, 41, 41);
	margin: 12.5% 52%;
	color:green;
	font-family: 'Arial Narrow';
	position: absolute;
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(2px 4px 4px #000000);
}

#fourthumg{
	width:18.5%;
	height: 18%;
	z-index: 4;
	letter-spacing: 1px;
	border: 2px solid rgb(41, 41, 41);
	margin: 12.5% 74%;
	color:green;
	font-family: 'Arial Narrow';
	position: absolute;
	background-color: rgb(0, 0, 0);
	filter: drop-shadow(2px 4px 4px #000000);
}

#isover{
	width:5% ;
	position: absolute;
	height: 10%;
	
	z-index: 10;
	right: 57.25%;
	top:174%;
}

#gen{
	width:5% ;
	position: absolute;
	height: 10%;
	
	z-index: 10;
	right: 57.25%;
	top:174%;
	
}

#isovertwo{
	width:5% ;
	position: absolute;
	height: 10%;
	z-index: 10;
	right: 51%;
	top:174%;
	
}

#Namekbutt{
	width:5% ;
	position: absolute;
	height: 10%;
	
	z-index: 10;
	right: 57.25%;
	top:174%;
	
}

#backbutt{
	width:5% ;
	position: absolute;
	height: 10%;
	z-index: 10;
	right: 51%;
	top:174%;
	
}

#genbackbutt{
	width:5% ;
	position: absolute;
	height: 10%;
	z-index: 10;
	right: 51%;
	top:174%;
	
}

#isoverthree{
	width:5% ;
	position: absolute;
	height: 10%;
	z-index: 10;
	right: 44.5%;
	top:174%;
	
	
}


#isoverfour{
	width:5% ;
	position: absolute;
	height: 10%;
	z-index: 10;
	right: 38.25%;
	top:174%;
	
	
}
#secondumgtag{
	width: 55%;
	height: 5.5%;
	top:11%;
	right:28.5%;
	color: #66ff66;
	text-align: center;
	font-family: 'Arial Narrow';
	position: absolute;
	z-index: 6;
	visibility: hidden;
	letter-spacing: 2px;
}

#firstumgtag{
	width: 55%;
	height: 5.5%;
	top:11%;
	right:58.5%;
	color: #66ff66;
	text-align: center;
	font-family: 'Arial Narrow';
	position: absolute;
	z-index: 6;
	visibility: hidden;
	letter-spacing: 2px;
}


#lfirstumgtag{
	width: 55%;
	height: 5.5%;
	top:11%;
	right:58.5%;
	color: #66ff66;
	text-align: center;
	font-family: 'Arial Narrow';
	position: absolute;
	z-index: 6;
	visibility: hidden;
	letter-spacing: 2px;
}


#loggedin{
	width: 95%;
	height: 95%;
	position: absolute;
	right:2.5%;
	top:2.5%;
	z-index: 3;

	
}

#entirebg{
	width: 100%;
	
	height: 100%;
	opacity: 0.5;
}


#logbuttons{
	position: absolute;
	top:10%;
	width: 92%;
	height: 80%;
	margin:0 4%;
	z-index: 10;
	
}

#greenbeans {
	position: absolute;
	width: 100%;
	height: 100%;
	padding: 10px;
	border: 0px solid gray;
	margin: 40;
	right: 0%;
	top: 0%;
	opacity: 1;
	z-index: 10;
	filter: drop-shadow(0px 4px 4px #222d33);
	//visibility: hidden;
}

#greenbeanss {
	position: absolute;
	width: 34.7%;
	height: 85%;
	padding: 10px;
	border: 0px solid gray;
	margin: 40;
	right: 33.3%;
	top: 5.5%;
	opacity: 0.3;
	z-index: 10;
	filter: drop-shadow(0px 4px 4px #222d33);
	//visibility: hidden;
}




#playerdata {
	position: absolute;
	width: 96%;
	height: 8%;
	padding: 10px;
	border: 0px solid gray;
	margin: 40;
	right: 0%;
	top: 0%;
	opacity: 1;
	z-index: 3;
}


#disclaimer {
	position: absolute;
	width: 28%;
	height: 8%;
	padding: 10px;
	right: 2.5%;
	top: 1%;
	background-color: rgb(68, 219, 116);
	opacity: 1;
	border: 2px solid rgb(57, 57, 57);
	text-align: center;
	z-index: 9;
	font-size: 80%;
	letter-spacing:1px;
	filter: drop-shadow(0px 4px 4px #222d33);
}
#stats {
	position: absolute;
	width: 22.15%;
	height: 10%;
	padding: 10px;
	border: 2px solid rgb(29, 29, 29);
	margin: 40;
	right: 5%;
	top: 10%;
	background-color: black;
	opacity: 0.5;
	filter: drop-shadow(0px 4px 4px #222d33);
	z-index: 10;
}


#statscase {
	position: absolute;
	width: 100%;
	height: 100%;
	top:30%;
	right:0%;
	color: white;	
	text-align: center;
	filter: drop-shadow(0px 4px 4px #222d33);
	z-index: 10;
	
	font-family: "Arial Narrow";
}

#content {
	position: absolute;
	width: 22.15%;
	height: 43%;
	padding: 10px;
	border: 2px solid rgb(31, 31, 31);
	margin: 40;
	right: 5%;
	top: 23.5%;
	color: white;
	text-align: center;
	background-color: black;
	opacity: 0.5;
	filter: drop-shadow(2px 4px 4px #222d33);
	z-index:10;
}

#contover{
	font-family: 'Arial Narrow';
	font-size: 100%	;
	letter-spacing: 1px;
	color:rgb(118, 118, 118);
}


#back {
	position: absolute;
	margin: 40;
	width: 95%;
	height: 96%;
	right: 2%;
	top: 150%;
	z-index: 3;
	
}

#actualback {
	position: relative;
	background-color: black;
	opacity: 0.5;
	margin: 40;
	width: 100%;
	height: 100%;
	right: 0.7%;
	top: -2%;
	border:2px solid rgb(45, 45, 45);
	background-color: black;
	opacity: 0.7;
	z-index: 2;
	filter: drop-shadow(0px 4px 4px #222d33);
}



#disc {
	position: absolute;
	width: 100%;
	height: 3%;
	padding: 10px;
	
	margin: 40;
	right: 0px;
	top: 0px;
	background-color: rgb(67, 67, 67);
	opacity: 1;
	z-index: 1;
	
}






#head {
	position: absolute;
	right: 20%;
	top: -20%;
	letter-spacing: 1px;
	
	transform: rotate(180deg);
	color: rgb(31, 31, 31);
	border: 0px solid gray;
	z-index: 8;
	
}

#heads {
	position: absolute;
	right: 20%;
	transform: rotate(180deg);
	top: -20%;
	z-index: 8;
	color:transparent;
	letter-spacing: 1px;
	
}


#umgtwo {
	position: absolute;
	width: 200px;
	height: 20px;
	padding: 10px;
	border: 0px solid gray;
	margin: 40;
	right: 1295px;
	top: 40px;
	background-color: lightgreen;
	opacity: 0.7;
	filter: drop-shadow(0px 3px 3px #222d33);
}

#login {
	position: absolute;
	width: 200px;
	height: 30px;
	padding: 10px;
	border: 2px solid gray;
	margin: 40;
	right: 735px;
	top: 580px;
	background-color: rgb(0, 0, 0);
	opacity: 0.5;
}

#test {
	position: absolute;
	left: 70px;
	top: -15px;
	line-height: 43px;
	
}



#love {
	position: fixed;
	top: 525px;
	background-color:red;
}



#cards {
	position: absolute;
	width: 100%;
	height: 11%;
	padding: 10px;
	border: 0px solid gray;
	margin: 40;
	right: 0px;
	top: 252%;
	background-color: rgb(63, 63, 63);
	opacity: 1;
}

</style>
