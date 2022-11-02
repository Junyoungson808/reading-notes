# Reading

## What is Role Based Access Control (RBAC)?

1. What is Role Based Access Control (RBAC)? 
  - network restrictions based on a person's role within an organization.
2. Share some an example of RBAC including all possible CRUD operations and correlating roles.
  - Different roles a user can have in a application from a general user who has the ability to view(GET) and someone with probably admin or Higher access rights can update or post new data (PUT / POST / DELETE). These would likely be controlled with a RBAC.
3. What are the Benefits of RBAC?
  1. Reducing admin work and IT support
  2. Maximizing operational efficiency
  3. Improving compliance

<--- Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named. --->

## [react-cookie library](https://www.npmjs.com/package/react-cookie)

## [react-cookies component](https://www.npmjs.com/package/react-cookies)

1. Describe some react-cookie features.
// Root.jsx
import React from 'react';
import App from './App';
import { CookiesProvider } from 'react-cookie';

export default function Root() {
  return (
    <CookiesProvider>
      <App />
    </CookiesProvider>
  );
}

2. Describe some react-cookies features.
import { Component } from 'react'
import cookie from 'react-cookies'
 
import LoginPanel from './LoginPanel'
import Dashboard from './Dashboard'
 
class MyApp extends Component {
  constructor () {
    super()
 
    this.onLogin = this.onLogin.bind(this)
    this.onLogout = this.onLogout.bind(this)
  }
 
  componentWillMount() {
    this.state =  { userId: cookie.load('userId') }
  }

3. Which library would you prefer would you prefer? Why?
  - might go with the cookie one, being we are using Provider currently in our labs and maybe practice what we are using and not jump to something new. 

## Reflection
What are your learning goals after reading and reviewing the class README?
  - reread and motivate myself to continue ingesting material in class and on the internet. 