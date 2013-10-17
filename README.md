atdesk.co is seeking frontend guru
========================

		/* TL;DR:  Startup seeks Frontend Guru - 1st engineering hire - £32K-£40K + equity */

		$( "atdesk.co" ).requires({

			title: "Senior Frontend Developer",

			descr: {
					You: 	"Are a frontend web developer of at least 7.0 magnitude on the Richter scale. Your knowledge of Javascript, HTML and CSS tends to inflict suicidal thoughts on inferior developers.",
					We: 	"Are a newly funded tech startup doing really interesting things with professional networking (honestly, it’s possible). We are looking for our first engineering hire. You will be employee #3."
			},

			requirements: function( you ) {
				return
					you.understand( this ) &&

					you.skills( 'Javascript' ).level == LEVEL_MAX &&
					you.love( 'Javascript' ) && you.hate( 'Javascript' ) &&
					( you.haveUsed( 'AngularJS' ) || you.haveUsed( 'EmberJS' ) || you.haveUsed( 'Backbone' ) ) &&

					you.skills( 'HTML' ).level == LEVEL_MAX &&
					you.skills( 'CSS' ).level == LEVEL_MAX &&
					( you.haveUsed( 'LESS' ) || you.haveUsed( 'SASS' ) ) &&

					you.comfortableWith( 'responsibility' ) &&
					you.lookingFor( 'challenge' )
				;
			},

			desirables: function() {
				return [
					'Open Source Contributions',
					'nodeJS',
					'PHP',
					'Graphic Design'
				];
			},

			salary: {
				range_min: "£32,500",
				range_max: "£40,000",
				depends_on: function(you) { return you.experience() },
				bonus: "Equity stake in the company"
			},

			benefits: [
				"Get in on the ground floor of an exciting venture",
				"Chance to learn new things and work with cutting-edge tech",
				"Equity stake in the company",
				"Significant input in the product and company",
				“Work from home for up to 2 days a week (after probation)”,
				"Your choice of hardware / development platform",
				"Flexible hours (physical presence still required)",
				"Flexible holiday allowance",
				"David Beckham was shooting across from our building the other day (nobody was hurt).",
			],

			notes: [
				"Physical presence is required (no full time telecommuting).",
				"Formal education will not be a deciding factor. If you have one, great. If you're self-taught, equally great."
			]

		});

