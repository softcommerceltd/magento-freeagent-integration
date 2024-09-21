## Changelog

# Mage2Fa [1.1.0] 21 Sep 2024

### softcommerce/module-core [1.5.3]
- **Enhancement**: Introduce tooltip renderer for UI columns [#12]
- **Enhancement**: Introduce flattening array interface [#11]

### softcommerce/module-freeagent-client [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-contact [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-contact-profile [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-contact-profile-schedule [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-contact-rest-api [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-creditmemo [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-creditmemo-profile [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-creditmemo-profile-schedule [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-creditmemo-rest-api [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-invoice [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-invoice-profile [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-invoice-profile-schedule [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-invoice-rest-api [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-profile [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-freeagent-rest-api [1.1.0]
- **Compatibility**: Introduced compatibility for Magento 2.4.7 [#1]

### softcommerce/module-profile [1.4.1]
- **Enhancement**: Preserve an array key for context services in `SoftCommerce\Profile\Model\ServiceAbstract\Service::initServices` [#4]

### softcommerce/module-profile-config [1.2.12]
- **Compatibility**: Introduce support for Magento 2.4.7 [#4]

### softcommerce/module-profile-history [1.2.8]
- **Compatibility**: Introduced support for PHP 8.3

### softcommerce/module-profile-queue [1.1.1]
- **Compatibility**: Introduced support for PHP 8.3

### softcommerce/module-profile-schedule [1.3.6]
- **Compatibility**: Introduced support for PHP 8.3

# Package: softcommerce/module-core

### Version 1.3.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.3.5
- **Feature**: Added new CLI to clean up the static view files from `pub/static` and `var/vew_processed` directories.
- **Compatibility**: Compatibility with Magento 2.4.6 [CE|EC|ECE].

### Version 1.3.4
- **Enhancement**: Added improvements and compatibility with php 8.[0.1] to `SoftCommerce\Core\Framework\DataStorageInterface`.

### Version 1.3.3
- **Enhancement**: Added json content renderer to UI listing columns component.

### Version 1.3.2
- **Enhancement**: Minor improvements to DataStorage functionality.

### Version 1.3.1
- **Enhancement**: Added an option to SKU storage to retrieve data by `entity_id`.

### Version 1.3.0
- **Enhancement**: Added an option to provide custom database columns in `SoftCommerce\Core\Model\Utils\SkuStorageInterface`
  model that's used to retrieve product entity data in array format.

### Version 1.2.9
- **Fix**: Applied a fix to license compatibility.

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.7
- **Enhancement**: Added option to store multidimensional data to `SoftCommerce\Core\Framework\DataStorageInterface::setData`.

### Version 1.2.6
- **Enhancement**: Improvements to `SkuStorage` functionality.

### Version 1.2.5
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.3
- **Fix**: JQMIGRATE: HTML tags must be properly nested and closed.

### Version 1.2.2
- **Enhancement**: Changes to PDT.

### Version 1.2.1
- **Enhancement**: [M2P-7] Add support for sequence entity ID generation to `\SoftCommerce\Core\Model\Utils\GetEntityMetadata`.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.3
- **Feature**: New module to handle Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.2
- **Feature**: Added new entity data storage for request and response queries.
- **Compatibility**: Compatibility with removed \Laminas\Log\Loger package.

### Version 1.0.1
- **Feature**: Added data storage including output filters to framework.

### Version 1.0.0
- **Feature**: [SCMC-1] New module to global functionality for dependant modules.

# Package: softcommerce/module-freeagent-client

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle client entity.

# Package: softcommerce/module-freeagent-contact

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle client contacts.

# Package: softcommerce/module-freeagent-contact-profile

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle contact profile.

# Package: softcommerce/module-freeagent-contact-profile-schedule

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.1
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.0
- **Feature**: New module to handle contact profile schedule.

# Package: softcommerce/module-freeagent-contact-rest-api

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.1
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.0
- **Feature**: New module to handle Contact REST API requests.

# Package: softcommerce/module-freeagent-creditmemo

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle sales creditmemo.

# Package: softcommerce/module-freeagent-creditmemo-profile

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle creditmemo profile.

# Package: softcommerce/module-freeagent-creditmemo-profile-schedule

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.1
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.0
- **Feature**: New module to handle creditmemo profile schedule.

# Package: softcommerce/module-freeagent-creditmemo-rest-api

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle Creditmemo REST API requests.

# Package: softcommerce/module-freeagent-invoice

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle sales invoices.

# Package: softcommerce/module-freeagent-invoice-profile

### Version 1.0.6
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.5
- **Fix**: Applied a fix to payment capture case for invoice import.

### Version 1.0.4
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).
- **Enhancement**: Added batch processor for invoice export.

### Version 1.0.3
- **Enhancement**: Applied additional submission event: "order" to enable submission of invoices based on order entity.

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle invoice profile.

# Package: softcommerce/module-freeagent-invoice-profile-schedule

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.1
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.0
- **Feature**: New module to handle invoice profile schedule.

# Package: softcommerce/module-freeagent-invoice-rest-api

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.1
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.0
- **Feature**: New module to handle Invoice REST API requests.

# Package: softcommerce/module-freeagent-profile

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle profile entity.

# Package: softcommerce/module-freeagent-rest-api

### Version 1.0.4
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6-p1 and PHP 8.2.0

### Version 1.0.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.6 and PHP 8.2.0

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle client REST API.

# Package: softcommerce/module-profile

### Version 1.3.2
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.3.1
- **Enhancement**: Added process validation chain to allow simpler profile process interception.

### Version 1.3.0
- **Enhancement**: Added an option to enable / disable history logging per profile.
- **Enhancement**: [M2P-10] Added a performance improvement to profile history where messages are now saved in batches.

### Version 1.2.9
- **Enhancement**: Moved mass status action for schedules from `SoftCommerce_Profile` to `SoftCommerce_ProfileSchedule`

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.7
- **Fix**: Applied a fix to `isDataSerialized` UI select argument, where element type select failed to retrieve values for serialised data type.

### Version 1.2.6
- **Enhancement**: Added new event `softcommerce_profile_config_save_before` to profile save action.

### Version 1.2.5
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.3
- **Enhancement**: Changes to PDT.

### Version 1.2.2
- **Enhancement**: Added ability to change profile schedule within profile list page.

### Version 1.2.1
- **Compatibility**: Compatibility with PHP 8.x

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [SCP-1] New module to handle multiple profile entities.

# Package: softcommerce/module-profile-config

### Version 1.2.8
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2
- **Enhancement**: Ability to export / import profile config data. #1

### Version 1.2.7
- **Fix**: Applied a fix to `SoftCommerce\ProfileConfig\Model\AbstractConfig::getConfigDataSerialized` where return type must be an array.

### Version 1.2.6
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.2.5
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.4
- **Enhancement**: Changed `SoftCommerce\ProfileConfig\Model\AbstractConfig::getTypeId` to public to allow other modules access this method.

### Version 1.2.3
- **Enhancement**: Improvements to config data provider.

### Version 1.2.2
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.1
- **Enhancement**: Changes to PDT.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [SCP-2] New module used to handle profile configuration.

# Package: softcommerce/module-profile-history

### Version 1.2.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.5
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8.
- **Enhancement**: Added batch size limit to history data insert per statement.

### Version 1.2.3
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.2
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.1
- **Enhancement**: Changes to PDT.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [SCP-3] New module used to handle profile history.

# Package: softcommerce/module-profile-queue

### Version 1.0.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.0.5
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.0.4
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8.

### Version 1.0.3
- **Fix**: Added a fix to updated_at timestamp.

### Version 1.0.2
- **Enhancement**: Added ability to specify batch size, when adding entries to queue.

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle profile queue entity.

# Package: softcommerce/module-profile-schedule

### Version 1.3.1
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.3.0
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.2.9
- **Enhancement**: Moved mass status action for schedules from `SoftCommerce_Profile` to `SoftCommerce_ProfileSchedule`

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8.

### Version 1.2.7
- **Enhancement**: Added profile type ID filter to cron_schedule collection.

### Version 1.2.6
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.5
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.4
- **Enhancement**: Allow inactive schedule process in order to collect profile data. Move `active/inactive` condition to each profile instead.

### Version 1.2.3
- **Enhancement**: Changes to PDT.

### Version 1.2.2
- **Improvement**: [M2P-4] Re-initialise config cache after saving new schedule cron task.

### Version 1.2.1
- **Compatibility**: JS Modal: IE9 break script loading and avoid execution on iframe [#5]

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.1.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.2
- **Compatibility**: JS backward compatibility for script rendering 2.3.5 - 2.4.2

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.2 [#6]

### Version 1.0.0
- **Feature**: [SCP-4] New schedule module used to handle profile schedules.
