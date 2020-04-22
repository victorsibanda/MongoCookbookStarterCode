# Mongo Cookbook

The purpose of this Cookbook is to download MongoDB. The cookbook sets up the config files (Service and Mongod). Which it can be used with an application.

## Pre-requisites
- Chef (https://downloads.chef.io/chef-workstation/0.17.5)

## What is Chef

Chef is a configuration management tool which allows you to provision files for installation. Whilst being infrastructure agnostic. Chef allows machine setup on physical machine, in the cloud and virtual machines. Which means all the files will be on the system when you boot it up.

## Clone

`git clone git@github.com:victorsibanda/MongoCookbookStarterCode.git`

## List of What is Installed
- MongoDB from Source

## Commands

### Test locally
Unit Test
`chef exex rspec`

Integration Test
`kitchen test`


### Test in AWS
`KITCHEN_YAML=kitchen_cloud.yml kitchen test`
