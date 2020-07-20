# Tizen Studio

<style>
/* Reset */

html, body, div, span, applet, object, iframe, {
		font-size: 70%;
		vertical-align: baseline;
	}
	body {
		line-height: 1;
	}
	body {
		-webkit-text-size-adjust: none;
	}

/* Box Model */

	*, *:before, *:after {
		-moz-box-sizing: border-box;
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
	}

/* Section/Article */

	section.special, article.special, header.special {
		text-align: center;
	}

/* Feature */

	.features {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
	}

	.feature {
		padding: 2em 2em 0.1em 2em;
		border-style: solid;
		border-width: 1px;
		margin-left: -1px;
		margin-top: -1px;
		width: 33.33333%;
	}


		@media screen and (max-width: 1280px) {

			.feature {
				padding: 2em 1.5em 0.1em 1.5em;
			}

		}

		@media screen and (max-width: 736px) {

			.feature {
				padding: 2em 1em 0.1em 1em;
				width: 50%;
			}

		}

		@media screen and (max-width: 480px) {

			.feature {
				padding: 2em 0.5em 0.1em 0.5em;
				width: 100%;
			}

		}

	.feature {
		border-color: #e3e3e3;
	}

</style>
<section id ="main">

This section explains about options available to install Tizen Studio on your development hardware. Tizen Studio runs on all major operating systems like Windows, macOS, Ubuntu. You can install any release of Tizen Studio. However, it is recommended that you install the most recent release. 
- Plan your installation: check for the necessary hardware and software requirements. 
- Install Tizen Studio:  follow the installation guides for each operating system.
- Configure: After installation, to have optimal development experience, configure various Tizen Studio components.  

Tizen Studio runs on Windows, Ubuntu, as well as macOS and for installation guide, click the following as per target operating system: 
<!-- tiles-->
<section id="one" class="wrapper special">
		<div class="inner">
			<header class="major">
			</header>
                        <div class="features">
                        <div class="feature">
                        <img src="./media/win.png">
                         <h3><a href="native-tools/index.md">Windows&reg</a></h3>	
                        </div>
						<div class="feature">
							<i class="fa fa-copy"></i>
							<img src="./media/linux1.png">
							<h3><a href= "web-tools/index.md">Ubuntu&reg</a></h3>
						</div>
						<div class="feature">
							<i class="fa fa-paper-plane-o"></i>
							<img src="./media/apple1.png">
                            <h3><a href= "configurable-sdk/configurable-sdk.md">macOS&reg</a></h3>
						</div>
					</div>
				</div>
			</section>