# paper-contact  [![Bower version](https://badge.fury.io/bo/paper-contact.svg)](http://badge.fury.io/bo/paper-contact)

A collection of components for contact information in Material Design build with [Polymer 1.x](https://www.polymer-project.org)

![Screenshot](/doc/paper-contact.png "Screenshot")

## Usage

`bower install paper-contact`

## Continuous integration

[Travis-CI](https://travis-ci.org/Collaborne/paper-contact) [![Travis state](https://travis-ci.org/Collaborne/d3-progress-meter.svg?branch=master)](https://travis-ci.org/Collaborne/paper-contact)

##&lt;paper-contact-address&gt;

Component for address contact details, that triggers the opening of Google Maps to the specified address on tap.

```html
<paper-contact-address latitude="51.5287718" longitude="-0.2416798">London</paper-contact-address>
```

### Properties

Property         | Type   | Description                       | Example
---------------- | ------ | --------------------------------- | -------
**Content Text** | String | Address                           | London
**latitude**	 | Number | Latitude of the desired location  | 51.5287718
**longitude**	 | Number | Longitude of the desired location | -0.2416798

##&lt;paper-contact-email&gt;

Component for email contact details, that triggers the opening of the email client on tap.

```html
<paper-contact-email>email@example.com</paper-contact-email>
```

### Properties

Property         | Type   | Description                                                              | Example
---------------- | ------ | ------------------------------------------------------------------------ | -------
**Content Text** | String | Email address 															 | email@example.com

##&lt;paper-contact-linkedin&gt;

Component for LinkedIn contact details, that triggers the opening of the linkedIn profile on tap.

```html
<paper-contact-linkedin>https://www.linkedin.com/in/profile</paper-contact-linkedin>
```

### Properties

Property         | Type   | Description                                                              | Example
---------------- | ------ | ------------------------------------------------------------------------ | -------
**Content Text** | String | LinkedIn profile														 | https://www.linkedin.com/in/profile

##&lt;paper-contact-mobile&gt;

Component for mobile contact details, that triggers the native call function for the provided number on tap.

```html
<paper-contact-mobile>+1-292-613-3742</paper-contact-mobile>
```

### Properties

Property         | Type   | Description                                                              | Example
---------------- | ------ | ------------------------------------------------------------------------ | -------
**Content Text** | String | Mobile number															 | +31123456789

##&lt;paper-contact-phone&gt;

Component for generic phone contact details, that triggers the native call function for the provided number on tap. Shows a different icon that the more specific 'mobile' component.

```html
<paper-contact-phone>+1-873-217-3442</paper-contact-phone>
```

### Properties

Property         | Type   | Description                                                              | Example
---------------- | ------ | ------------------------------------------------------------------------ | -------
**Content Text** | String | Phone number															 | +31123456789

##&lt;paper-contact-skype&gt;

Component for skype contact details, that triggers the skype call function for the provided skype id on tap. 

```html
<paper-contact-skype>your-id</paper-contact-skype>
```

### Properties

Property         | Type   | Description                                                              | Example
---------------- | ------ | ------------------------------------------------------------------------ | -------
**Content Text** | String | Skype ID															 	 | your-id

##&lt;paper-contact-twitter&gt;

Component for twitter contact details, that opens the provided twitter profile in a new window on tap. 

```html
<paper-contact-twitter>@profile</paper-contact-twitter>
```

### Properties

Property         | Type   | Description                                                              | Example
---------------- | ------ | ------------------------------------------------------------------------ | -------
**Content Text** | String | Twitter profile															 | @profile


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    
