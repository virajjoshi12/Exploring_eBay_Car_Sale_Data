# Exploring_eBay_Car_Sale_Data
This project shall work with a dataset of used cars from eBay Kleinanzeigen, a classifieds section of the German eBay website.

The dataset was originally scraped and uploaded to Kaggle by user [orgesleka](https://www.kaggle.com/orgesleka). The original dataset isn't available on Kaggle anymore, but you can find it [here](https://data.world/data-society/used-cars-data).

One modification has been made from the original dataset:

50,000 data points have been sampled from the full dataset.
The data dictionary provided with the data is as follows:

- `dateCrawled`: When this ad was first crawled. All field values are taken from this date.

- `name`: Name of the car.

- `seller`: Whether the seller is private or a dealer.

- `OfferType`: Whether the seller is private or a dealer.

- `price`: The price on the ad to sell the car.

- `abtest`: Whether the listing is included in an A/B test.

- `vehicleType`: The vehicle Type.

- `yearOfRegistration`: The year in which the car was first registered.

- `gearbox`: The transmission type.

- `powerPS`: The power of the car in PS.

- `model`: The car model name.

- `kilometer`: How many kilometers the car has driven.

- `monthOfRegistration`: The month in which the car was first registered.

- `fuelType`: What type of fuel the car uses.

- `brand`: The brand of the car.

- `notRepairedDamage`: If the car has a damage wich is not yet repaired.

- `dateCreated`: The date on which the eBay listing was created.

- `nrOfPictures`: The number of pictures in the ad.

- `postalCode`: The postal code for the location of the vehicle.

- `lastSeenOnLine`: When the crawler saw this ad last online.

The aim of this project is to clean the data and analyse the included used car listings. We shall now import the libraries we need and read the dataset into pandas.
