# Matvei Pustovalov

## Contact info

Location: Pisek, Czechia
E-mail: pustovalov.mv@ya.ru
Telegram: [@pustoy_m](https://t.me/pustoy_m)
[LinkedIn](https://www.linkedin.com/in/pustoi/)

## About me

Self-taught web developer with over seven years of experience in developing websites and marketing promotion of web products for small and medium-sized businesses in Russia.

I manage web development projects:

- supervising the quality and terms of development.
- delegating html-layout job
- selecting new performers for the project and manage the development schedule

I'm taking a free course from the community [The Rolling Scopes](http://rollingscopes.com/) in order to validate myself and test the accumulated knowledge over many years of practical development

## Hard skills & instruments

- HTML-first layout for LAMP, with templating: Pug, Twig, etc;
- CSS, SASS (prefer SCSS syntax), PostCSS;
- **Methodology:** BEM, a11y principles, Progressive enhancement, Feature detection
- **JavaScript:** ES6 syntax, React, Vue.js;
- **Automatization:** Gulp, Webpack;
- **Version control:** Git, GitHub, Bitbucker;
- **Project managing:** Notion, Wrike, Basecamp, Jira, Trello, Bitrix24;
- **Design:** Figma, AdobeXD, Zeplin, Avocode, Photoshop, Illustrator.

## Code examples

```javascript
/**
 * https://leetcode.com/problems/contains-duplicate/
 * @param {number[]} nums
 * @return {boolean}
 */
const containsDuplicate = (nums, numsSet = new Set()) => {
  for (const num of nums) {
    if (numsSet.has(num)) return true;

    numsSet.add(num);
  }

  return false;
};
```

See more in [GitHub profile](https://github.com/pustoym).
