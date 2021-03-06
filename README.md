# token-generator
**This is the official repository for token-generator app**

[![Test Coverage](https://codeclimate.com/github/ArcanaMagus/token-generator/badges/coverage.svg)](https://codeclimate.com/github/ArcanaMagus/token-generator/coverage)
[![Code Climate](https://codeclimate.com/github/ArcanaMagus/token-generator/badges/gpa.svg)](https://codeclimate.com/github/ArcanaMagus/token-generator)
[![Build Status](https://travis-ci.org/ArcanaMagus/token-generator.svg?branch=token)](https://travis-ci.org/ArcanaMagus/token-generator)
[![Coverage Status](https://coveralls.io/repos/ArcanaMagus/token-generator/badge.svg?branch=token&service=github)](https://coveralls.io/github/ArcanaMagus/token-generator?branch=token)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)]
(https://github.com/ArcanaMagus/Malware/blob/Malware/LICENSE)

An implement of the  hmac-algorithm, for generating access keys to the REST API

This app can be used to generate an hmac or sha-sum algorithm based secure access code,
for a variety of purposes. Such as  creating a custom login page for a web application.

#Usage

**Example**

<code> hmac.new("Enter data here") // @Newbies replace this with your own data </code>

**Explanation**

The sub-apps of token-generator may use the <code>.hexdigest()</code> method to convert your,
pre generated codes or data to a secure authentication key. To use this app effectively,
you should pipe the data required for your access key directly to the <code>hmac</code> or,
<code>md5</code> else <code>sha</code> function.

When used in combination with the <code>.new</code> operator a new access key based on your,
selected algorithm, (e.g. <code> sha-sum, md5, hmac </code>). This access key will be generated,
with the data you have provided. 

#Note

This build is failing intentionally because the system configuration is catching errors,
in various modern browsers (as intended) [ **See Code Quality** ]
