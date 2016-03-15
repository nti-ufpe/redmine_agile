### Redmine Agile

#### About
Plugin that brings agile functionalities to [Redmine](http://www.redmine.org) and [RedmineCRM](http://http://www.redminecrm.com/)

#### Features
- Ajax agile boards
- Version planner
- Story points
- Swin lanes
- AGile charts (burndown, cumulative flow, velocity)
- Colors

#### Compatibility
- Redmine 2.x
- Redmine 3.x
- Browsers: Chrome, Safari, Internet Explorer and Firefox

#### Installation
1. Clone repository into Redmine **plugins** folder:
`$ git clone https://github.com/nti-ufpe/redmine_agile`
2. Run bundle install
`$ bundle install`
3. Migrate database
`$ rake redmine:plugins NAME=redmine_agile`
4. Start application

#### Version
1.4.0 - 02/09/2016


#### License
Copyright (C) 2011-2016 Kirill Bezrukov - [RedmineCRM](http://www.redminecrm.com)
