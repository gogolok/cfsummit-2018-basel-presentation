# Verifying Open Service Broker API Compliance and Testing Production Broker Deployments

# Who We Are


![](https://pbs.twimg.com/profile_images/918769388731244544/d2YYAKr8_400x400.jpg)

Oliver Wolf

@wolfoliver

Lead Platform Engineer @anynines


![](https://pbs.twimg.com/profile_images/620716730961260544/45S15RRP_400x400.jpg)

Robert Gogolok

@gogolok

Platform Engineer @anynines

# In the Beginning

![](https://bosh.io/docs/images/logo-full.png)

![](https://www.cloudfoundry.org/wp-content/uploads/2017/01/CFF_Logo_vertical_RGB.png)

![](https://webassets.mongodb.com/_com_assets/cms/mongodb-logo-rgb-j6w271g1xn.jpg)

![](http://download.redis.io/logocontest/82.png)

# Tests

- Unit Tests for the Service Broker
- Unit Tests for BOSH Releases
- Smoke Testing

# Integration Testing

- pick existing smoke tests implementatons as a basic idea
- DRY
- bindingo (Service Binding Checker App)

# Integration Testing

FIXME: Overview Picture instead of text

- Setup Environment (CF specific, service specific)
- General Tests (cf cs, cf bs, cf create-service-key, cf ds)
- Service Specific Tests
  - Dashboard
  - Backup/Restore
  - Monitoring

# Integration Testing

Demo

# OSBAPI Test Suite

- by-product
- needs tuning

FIXME: image

# Questions?

# Thanks
