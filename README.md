

import SoftwareEngineer from 'tyler-bolty';

class Introduction extends SoftwareEngineer {
  this.intro    = 'Passionate full stack developer with a particular knack for backend intricacies,
                   API design, and data modeling. I thrive on crafting high-quality web applications
                   and love diving deep into complex challenges.';
}

class Bio extends SoftwareEngineer {
  this.name     = 'Tyler Bolty';
  this.title    = 'Full Stack Software Engineer';
  this.company  = 'Bamboo Rose';
  this.location = 'Charlotte, NC, USA';
}

class Skills extends SoftwareEngineer {
  this.languages = ['TypeScript', 'Go', 'SQL', 'Java', 'HTML', 'CSS']
  this.databases = ['MongoDB', 'NoSQL Databases', 'PostgreSQL', 'SQL Databases']
  this.frameworksAndLibraries = {
    backend: ['Node', 'NestJS', 'GraphQL', 'Express.js', 'Redis', 'Socket.io'],
    frontend: ['React', 'Vue', 'Angular', 'Next.js']
  }
  this.devOps = ['Docker', 'AWS', 'Terraform', 'CircleCI', 'CI/CD']
  this.other = ['AWS S3', 'Handlebars', 'Handsontable', 'SCSS', 'Postman', 'Sendgrid', 'Jira']
}
