# Coercion and Truthy/Falsey

## Double Equals, Triple Equals, and Type Coercion

```javascript
23 == '23' // this will equal true
23 === '23' // this will equal false
```

! "bang" operator 

```javascript
!=
!==
```

## Truthy and Falsy

```javascript
// All of the following are inherently falsey:

False
// False is False. Makes sense, right?

0
// 0 is the only falsey Number

""
// an empty string is falsey

null
// a null, or empty value, is falsey.

undefined
// an object that has not been defined is considered falsey.

NaN
// Not a Number. You'll learn more about NaN as we go on.
```