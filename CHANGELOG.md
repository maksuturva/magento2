# Changelog
All notable changes to this module will be documented in this file.
 
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/). 

## [1.4.1] - 2021-03-21
### Changed
 - Removed MasterPass payment method
### Fixed
 - Observer PaymentMethodIsActive fixed to check class interface

## [1.4.0] - 2021-03-17
### Added
 - Maksuturva Generic dynamic payment method icons on Payment page
### Changed
 - some Maksuturva -> Svea Payments text changes 

## [1.3.0] - 2020-04-07
### Added
 - Credit memo Refund feature

## [1.2.0] - 2019-11-25
### Changed
 - Piimega -> Svea. Paths changed and README.md installation instructions updated
 - maksu 37 payment status change from hash calc to basic auth

### Fixed
 - GiftCard fixes from pull request Feature/maksu 36 support mgo giftcard
 - Model/ResosurceModel/Method.php check for empty imageurl added

## [1.1.0] - 2019-09-09
### Added
- MINOR Add support for Magento gift card.