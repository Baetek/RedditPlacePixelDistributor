# RedditPlacePixelDistributor

Webapp to allow faster graphic generation in the Place by allowing uploading or drawing a picture of a custom size and creates a unique link for that picture which that user can then share.

Visitors that enter this shared link are given coordinates for a pixel and the color to make it.

Once all the pixels required to make the image are assigned the app should just loop through them if more visitors come. Though if we end up going further we could instead assign based on a parse of the current state of the Place and a user supplied image start coordinate, to auto-assign visitors for damage repair.
