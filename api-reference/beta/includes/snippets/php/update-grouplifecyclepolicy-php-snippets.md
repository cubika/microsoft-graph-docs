---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new GroupLifecyclePolicy();
$requestBody->setGroupLifetimeInDays(180);

$requestBody->setManagedGroupTypes('Selected');

$requestBody->setAlternateNotificationEmails('admin@contoso.com');



$result = $graphServiceClient->groupLifecyclePoliciesById('groupLifecyclePolicy-id')->patch($requestBody);


```