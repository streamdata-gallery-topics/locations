---
name: Coord
x-slug: coord
description: Coord is a mobility company that creates seamless mobility and self-driving
  experiences today through deep integrations. The company offers bike-share API,
  Curbs API, Tolls API, Routing API and etc.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
x-kinRank: "7"
x-alexaRank: "1035226"
tags: Locations
created: "2018-08-19"
modified: "2018-08-19"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/apis.md
specificationVersion: "0.14"
apis:
- name: Coord Bike Share API
  x-api-slug: coord-bike-share-api
  description: the-bike-share-api-is-a-comprehensive-api-that-provides-information-about-bike-sharesystems-including-available-bikes-and-prices-for-an-example-of-how-to-use-the-bike-share-api-see-the-a-hrefhttpscoord-coquickstartbikeshare-target-blankbike-share-guidea--examplesearch-for-a-bikecurl-g-httpsapi-coord-cov1bikelocationlatitude40-73935542longitude73-99931783radius-km0-1access-keyyour-api-keythe-api-methods-allow-you-to-search-for-available-bikes-and-get-quotes-on-bike-rentalsas-well-as-get-detailed-information-about-bike-share-systems-and-bike-share-locations-bike-share-systems-have-one-or-more-locations--since-bikes-in-a-bike-share-system-may-be-in-adock-or-individually-parked-a-bike-location-can-refer-to-either-a-dock-or-a-single-separatelyparked-bike--therefore-a-search-for-bike-locations-is-really-a-search-for-rideable-bikes-bikes-that-are-currently-inuse-or-otherwise-not-ready-for-rental-are-not-searchable-throughthis-api-the-simplest-method-to-call-is-locationreference0findbikesbylocation-with-a-targetlatitude-and-longitude-and-a-search-radius--this-will-return-all-available-locations-withinthat-radius-and-information-about-each-location-calling-quotereference0getquote-will-return-all-quotes-for-allsystems-or-if-provided-with-specific-system-ids-quotes-for-just-the-specified-systems-calls-to-systemsystem-idreference0getbikesystem-orlocationsystem-idlocation-idreference0getbikelocation-are-helpful-toget-more-information-about-individual-systems-or-locations-respectively-calling-systemreference0findbikesystemsbylocation-with-a-target-latitude-and-longitudeand-a-search-radius-will-return-all-systems-within-that-radius-and-information-about-eachsystem--quotes-and-passesquotes-are-the-cost-and-details-of-renting-a-single-bike-from-a-system--they-consist-of-aset-of-pass-types-where-each-type-defines-a-buyable-pass-for-a-system--a-passrepresents-the-right-to-rent-bikes-from-a-single-system-for-a-certain-length-of-time-or-acertain-number-of-rides--for-instance-you-could-see-a-single-ride-pass-a-single-day-passa-30day-pass-or-an-annual-pass-passes-also-come-with-usage-fees-that-represent-the-cost-of-riding-a-bike-for-a-certainlength-of-time-within-a-given-rental--to-model-systems-that-charge-solely-by-the-length-ofeach-ride-with-no-upfront-charge-we-return-a-single-0-pass-type-representing-the-systemspricing-in-general-with-charge-by-time-set-to-true--finally-we-have-information-about-thetax-rate-this-pass-could-be-subject-to-here-is-an-example-3day-pass-that-costs-24-00-where-rides-over-30-minutes-are-billed-at-5-per15-minutes---id-2--system-id-citibike--max-days-3--charge-by-time-false--cost-----currency-usd----amount-2400----usage-fees-----cost-------currency-usd------amount-500--------prorated-false----start-time-seconds-1800----fee-increment-seconds-900----tax-regions-----name-new-york-city----tax-rate-0-08875-------name-jersey-city----tax-rate-0-07--here-is-an-example-7-95-singleride-pass-with-usage-fees-and-tax-details-omitted--id-1--system-id-citibike--max-rides-1--charge-by-time-false--cost-----currency-usd----amount-795----usage-fees------------tax-regions----------and-heres-an-example-from-a-pay-as-you-go-system-that-charges-2-for-30-minutes-and-7-cents-aminute-thereafter--as-you-can-see-usage-fees-are-cumulative-they-all-get-charged-togetheras-a-single-ride-increases-in-length-and-passes-each-of-their-start-time-seconds-values---id-3--system-id-jumpdc--charge-by-time-true--usage-fees-----cost-------currency-usd------amount-200--------prorated-false----start-time-seconds-0-------cost-------currency-usd------amount-7--------prorated-false----start-time-seconds-1800----fee-increment-seconds-60----tax-regions----------
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data API, Relative Data API, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-openapi.md
- name: Coord Bike Share API
  x-api-slug: coord-bike-share-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/openapi.md
- name: Coord Curb Search API
  x-api-slug: coord-curb-search-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/openapi.md
- name: Coord Multimodal Routing API
  x-api-slug: coord-multimodal-routing-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/routing
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/openapi.md
- name: Coord Parking Access API
  x-api-slug: coord-parking-access-api
  description: the-parking-access-api-allows-you-to-authorize-one-of-your-end-users-to-park-at-a-supportedparking-location-by-means-of-creating-a-new-parkingsession-for-your-user-at-the-location-for-a-list-of-supported-locations-seea-hrefhttpscoord-codocssearchparking-target-blankthe-parking-search-apia-you-may-only-call-the-accessparking-api-using-parkinglocation-ids-returned-from-the-searchapi-for-locations-where-online-access-type-is-set-to-something-other-than-not-available-all-other-ids-will-be-rejected--parking-creating-a-sessionto-allow-a-user-to-park-at-a-given-lot-or-garage-you-create-a-session-for-that-user-atthe-location-you-can-create-a-new-session-by-callingpost-location-idsessionreference0createandretrievesessionscreateanewsessionwhich-will-return-a-new-session-that-either-is-already-started-has-an-end-time-set-orcontains-any-information-necessary-to-display-to-your-end-user-to-start-the-session-forexample-a-barcode-that-must-be-scanned-in-at-the-location-to-authorize-access--apicontrolled-sessionssessions-that-come-back-with-a-start-time-already-set-are-apicontrolled-meaning-thatthe-location-itself-has-no-way-of-telling-when-your-user-enters-or-leaves-but-insteaddepends-on-you-to-do-this-through-the-api--for-these-sessions-you-must-eventually-callput-location-idsessionsession-idendreference0endingsessionsendapreviouslystartedsessionto-end-the-session-at-which-point-billing-info-will-be-attached-and-returned-in-the-response-typically-you-would-provide-a-way-for-your-end-user-to-tell-you-that-they-are-leaving-theparking-lot-and-then-call-this--note-that-if-you-fail-to-call-this-method-you-risk-accruingthe-maximum-charge-possible-for-the-given-location--sitecontrolled-sessionsat-locations-that-have-a-means-of-telling-when-users-enter-and-leave-like-human-attendants-ora-barcode-scanner-the-session-end-time-and-billing-information-will-be-set-only-afterthe-user-ends-their-session-at-the-location-e-g--scans-out-with-a-barcode-or-checks-out-withan-attendant--in-such-cases-you-may-want-to-pollget-location-idsessionsession-idreference0retrieveanexistingsessionretrieveanexistingsessionuntil-an-end-time-exists-in-the-response--this-is-useful-to-provide-a-summarynotification-toyour-user-after-checkout-and-for-your-own-records-note-that-parkingsession-objects-last-forever--you-can-always-callget-location-idsessionsession-idreference0retrieveanexistingsessionretrieveanexistingsessionfor-information-on-a-session-that-you-created--maximum-stayssome-apicontrolled-and-sitecontrolled-sessions-may-be-subject-to-a-maximum-duration-whichmeans-that-after-a-set-amount-of-time-the-session-will-automatically-be-assigned-an-end-timeand-be-billed-for-usage-up-to-that-time--though-you-can-generally-avoid-this-by-callinga-hrefhttpscoord-codocssearchparking-target-blankthe-parking-search-apiabeforehand-to-determine-if-your-users-expected-parking-time-will-be-valid-at-a-locationsince-that-method-only-returns-locations-that-can-accept-parking-for-a-given-start-time-andduration-pair-your-user-might-still-stay-beyond-their-original-expected-duration-and-hit-amaximum-stay-time-you-can-poll-get-location-idsessionsession-idreference0retrieveanexistingsessionretrieveanexistingsession-todetermine-if-a-session-has-automatically-closed-and-notify-your-user-that-this-has-happened-if-this-happens-your-user-has-the-following-options---for-apicontrolled-sessions-your-user-should-leave-the-location-immediately-to-avoid-some--kind-of-enforcement-action-car-booting-towing-stickering-etc--note-that-you-will-not--need-to-explicitly-call--put-location-idsessionsession-idendreference0endingsessionsendapreviouslystartedsession-since-the--session-is-already-ended----for-sitecontrolled-sessions-your-user-may-or-may-not-be-able-to-check-out-using-the--redemption-info-provided-in-the-session--if-checkout-fails-gate-arm-does-not-go-up-your--user-may-have-to-resort-to-local-onsite-help-speaking-with-an-attendant-calling-posted--telephone-numbers-or-using-onsite-intercoms-for-assistance----finding-sessions--in-addition-to-querying-for-the-status-of-a-single-session-you-can-also-get-all-of-the--sessions-for-a-given-user-by-calling---get-sessionreference0retrieveauserssessionsretrieveauserssessions--this-will--return-both-the-currently-open-session-if-it-exists-and-all-closed-sessions---to-get-all-of-a-users-sessions-at-a-given-location-you-can-call--get-location-idsessionreference0createandretrievesessionsretrievealocationssessions-
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/access/parking
  tags: Parking, Tolls, Bikes, Routes, General Data API, Relative Data API, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-idsession-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-idsession-get-openapi.md
- name: Coord Parking Access API
  x-api-slug: coord-parking-access-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/access/parking
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/openapi.md
- name: Coord Parking Search API
  x-api-slug: coord-parking-search-api
  description: the-parking-search-api-is-a-readonly-service-to-answer-questionsabout-where-and-when-a-person-can-park-in-lots-and-garages--for-onstreet-parkinguse-the-curbs-api-finding-parking-locationsa-place-where-you-can-park-is-called-a-location--this-is-usually-either-a-surface-parkinglot-or-a-parking-garage--to-find-parking-locations-in-a-given-area-use-thelocationreference0getalistoflocations-request--this-will-return-an-object-for-each-open--location-in-that-area-ordered-by-distance-when-we-have-live-parking-availability-for-a-location-we-will-also-fill-inavailability-probability-for-it--this-represents-the-probability-that-there-will-be-at-leastthreshold-spaces-available-at-the-location--we-find-availability-probability-a-prettygreat-way-to-reason-about-parking-locations-which-may-have-uncertainty-around-theiravailability-both-at-the-current-time-and-in-the-future-when-someone-may-be-arriving-aftera-trip-getting-data-on-a-single-locationuse-locationreference0getasinglelocations-requests-to-get-the-same-information-aboutjust-one-location-accessing-a-lotyou-can-allow-your-mobile-users-to-check-into-and-out-of-select-locationsusing-the-parking-access-api--parking-rates-select-locations-will-have-a-rates-field-set-with-a-list-of-rates-which-can-be-displayed-toyour-end-users-for-a-rough-idea-on-the-price-of-parking-all-locations-will-include-a-total-price-if--parking-start-time-and-duration-m-are-setappropriately-
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/parking
  tags: Parking, Tolls, Bikes, Routes, General Data API, Relative Data API, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-openapi.md
- name: Coord Parking Search API
  x-api-slug: coord-parking-search-api
  description: the-parking-search-api-is-a-readonly-service-to-answer-questionsabout-where-and-when-a-person-can-park-in-lots-and-garages--for-onstreet-parkinguse-the-curbs-api-finding-parking-locationsa-place-where-you-can-park-is-called-a-location--this-is-usually-either-a-surface-parkinglot-or-a-parking-garage--to-find-parking-locations-in-a-given-area-use-thelocationreference0getalistoflocations-request--this-will-return-an-object-for-each-open--location-in-that-area-ordered-by-distance-when-we-have-live-parking-availability-for-a-location-we-will-also-fill-inavailability-probability-for-it--this-represents-the-probability-that-there-will-be-at-leastthreshold-spaces-available-at-the-location--we-find-availability-probability-a-prettygreat-way-to-reason-about-parking-locations-which-may-have-uncertainty-around-theiravailability-both-at-the-current-time-and-in-the-future-when-someone-may-be-arriving-aftera-trip-getting-data-on-a-single-locationuse-locationreference0getasinglelocations-requests-to-get-the-same-information-aboutjust-one-location-accessing-a-lotyou-can-allow-your-mobile-users-to-check-into-and-out-of-select-locationsusing-the-parking-access-api--parking-rates-select-locations-will-have-a-rates-field-set-with-a-list-of-rates-which-can-be-displayed-toyour-end-users-for-a-rough-idea-on-the-price-of-parking-all-locations-will-include-a-total-price-if--parking-start-time-and-duration-m-are-setappropriately-
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/parking
  tags: Parking, Tolls, Bikes, Routes, General Data API, Relative Data API, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationid-get-openapi.md
- name: Coord Parking Search API
  x-api-slug: coord-parking-search-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/parking
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/openapi.md
- name: Coord Tolls API
  x-api-slug: coord-tolls-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/tolling
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/openapi.md
- name: Coord Users API
  x-api-slug: coord-users-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/users
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/openapi.md
x-common:
- type: x-blog
  url: https://medium.com/coord
- type: x-blog-rss
  url: https://medium.com/feed/coord
- type: x-openapi
  url: https://jsapi.apiary.io/apis/coordprodsearchtolls.source
- type: x-api-stack
  url: http://coord.stack.network
- type: x-developer
  url: https://coord.co/docs/
- type: x-pricing
  url: https://coord.co/#pricing
- type: x-twitter
  url: https://twitter.com/coordcity
- type: x-website
  url: https://coord.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---