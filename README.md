# Facebook ads library scraper
Interested in using this scraper? Get it here: [Facebook ads library scraper](https://apify.com/curious_coder/facebook-ads-library-scraper)
## How it works

The Facebook ads library scraper is an Apify actor designed to extract information about ads run by facebook company pages. 

## Main Features

**Proxy Support:** To enhance reliability and avoid rate limiting issues, the actor supports proxy usage. You can provide a list of proxies that will be rotated automatically to ensure smooth and uninterrupted scraping.

**Scalability and Performance:** The actor is built on the Apify platform, which ensures scalability and excellent performance. It utilizes parallel processing to scrape multiple pages simultaneously, maximizing efficiency and minimizing the overall scraping time. 

**Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. This allows for seamless integration with other tools and platforms for further analysis and utilization.

**Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the actor has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

## Sample data

Here is the sample json output of this actor:

```json
{
	"adid": "0",
	"adArchiveID": "156624667418753",
	"archiveTypes": [],
	"categories": [
		0
	],
	"collationCount": 3,
	"collationID": 316138277474021,
	"currency": "",
	"endDate": 1693119600,
	"entityType": "person_profile",
	"fevInfo": null,
	"gatedType": "eligible",
	"hasUserReported": false,
	"hiddenSafetyData": false,
	"hideDataStatus": "NONE",
	"impressionsWithIndex": {
		"impressionsText": null,
		"impressionsIndex": -1
	},
	"isAAAEligible": true,
	"isActive": true,
	"isProfilePage": false,
	"pageID": "116703321481745",
	"pageInfo": null,
	"pageIsDeleted": false,
	"pageName": "Freelance Platform",
	"politicalCountries": [],
	"reachEstimate": null,
	"reportCount": null,
	"snapshot": {
		"ad_creative_id": "23857567921760603",
		"cards": [],
		"body_translations": {},
		"byline": null,
		"caption": "app-work.org",
		"cta_text": "Sign Up",
		"dynamic_item_flags": {},
		"dynamic_versions": null,
		"edited_snapshots": [],
		"effective_authorization_category": "NONE",
		"event": [],
		"extra_images": [],
		"extra_links": [],
		"extra_texts": [],
		"extra_videos": [],
		"instagram_shopping_products": [],
		"display_format": "image",
		"title": "Join in Appwork",
		"link_description": null,
		"link_url": "https://track.app-work.org/index.php?key=a4oxgv18qajfoqe5pdvk&utm_source=FaceBook&utm_campaign={{campaign.id}}&utm_content={{adset.id}}&utm_term={{ad.id}}&campaign_name={{campaign.name}}&adset_name={{adset.name}}&ad_name={{ad.name}}",
		"page_welcome_message": null,
		"images": [
			{
				"original_image_url": "https://scontent.fixe2-1.fna.fbcdn.net/v/t39.35426-6/367723806_238620161944079_8681096725247355970_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=cf96c8&_nc_ohc=ZFlPNCohyPUAX9oKame&_nc_ht=scontent.fixe2-1.fna&oh=00_AfD58pTNIYaIPoeKeZJPFy5OWzbZi8wKiujggyP9PRbiEQ&oe=64F0FB9D",
				"resized_image_url": "https://scontent.fixe2-1.fna.fbcdn.net/v/t39.35426-6/367454643_249439344673720_2615004650267393586_n.jpg?stp=dst-jpg_s600x600&_nc_cat=108&ccb=1-7&_nc_sid=cf96c8&_nc_ohc=h_5o-fQ-ADwAX9UZHlF&_nc_ht=scontent.fixe2-1.fna&oh=00_AfAIx_kkiknS6ErrU1a2CDdl_bh5E7LiB1C9RIqUXSpnkQ&oe=64F11AF0",
				"watermarked_resized_image_url": "",
				"image_crops": {}
			}
		],
		"videos": [],
		"creation_time": 1692093033,
		"page_id": 116703321481745,
		"page_name": "Freelance Platform",
		"page_profile_picture_url": "https://scontent.fixe2-1.fna.fbcdn.net/v/t39.35426-6/366617793_956429388794757_6739632606346544290_n.jpg?stp=dst-jpg_s60x60&_nc_cat=110&ccb=1-7&_nc_sid=cf96c8&_nc_ohc=8ki4Orb8Ct0AX82mZsu&_nc_ht=scontent.fixe2-1.fna&oh=00_AfADymstWPsx4WJXBaRviR1KzGznbkXAtY0Fil-F7oYkZQ&oe=64F13095",
		"page_categories": {
			"2202": "Website"
		},
		"page_entity_type": "person_profile",
		"page_is_profile_page": false,
		"instagram_actor_name": "",
		"instagram_profile_pic_url": "",
		"instagram_url": "",
		"instagram_handle": "",
		"is_reshared": false,
		"version": 3,
		"body": {
			"context": {},
			"markup": {
				"__html": "Get profit by publishing applications<br /> 📣 No special skills required!<br /> 🔹1-2 hours on average for one task<br /> 🔹Without tests and checks."
			},
			"callerHash": "214af1a3e04f5d8deb0cfcdb4a5c1dc1"
		},
		"brazil_tax_id": null,
		"branded_content": null,
		"current_page_name": "Freelance Platform",
		"disclaimer_label": null,
		"page_like_count": 348,
		"page_profile_uri": "https://facebook.com/100094788301266",
		"page_is_deleted": false,
		"root_reshared_post": null,
		"cta_type": "SIGN_UP",
		"additional_info": null,
		"ec_certificates": null,
		"country_iso_code": null,
		"instagram_branded_content": null
	},
	"spend": null,
	"startDate": 1692082800,
	"stateMediaRunLabel": null,
	"publisherPlatform": [
		"facebook"
	],
	"menuItems": []
}
```
