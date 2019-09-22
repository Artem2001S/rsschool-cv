# Resume

## First,Last Name
   * Artem Kazaryan

## Contact Info
   * E-mail: kazarynarm@Mail.ru
   * Phone Number: +7 (962) 246-29-03

## Summary:
   * Want to develop in front-end
   * Ready to perform difficult tasks to become better and more experienced

## Skills:
   * `HTML` `CSS`
   * `JavaScript` basics
   * `C#` `Entity Framework`
   * `SQL`
   * `Git`

## Code Examples - some kata from codewars:
### Task:

   >Friday 13th or Black Friday is considered as unlucky day. Calculate how many unlucky days are in the given year.
   >Find the number of Friday 13th in the given year.
   >Input: Year as an integer.
   >Output: Number of Black Fridays in the year as an integer.
   >Examples:
   >unluckyDays(2015) == 3
   >unluckyDays(1986) == 1

```javascript
   function unluckyDays(year){
     let res = 0;
     for (let i = 0; i <= 11; i++){
        let date = new Date(year,i,13);
        if (date.getDay() === 5) res++;
     }
    return res;
   }
```

## Experience
   Developed several freelance projects using C# WPF/WinForms + SQL and a portfolio site for a lighting designer.

## Education
  * I am studying at the 4th year of the college named after Konyaev.
  * [Codeacademy profile](https://www.codecademy.com/profiles/Sinclerr)
  * Now I am reading the book [`Functional Web Development with React and Redux`](http://shop.oreilly.com/product/0636920049579.do)

## English
  My level of English is pre-intermediate.
