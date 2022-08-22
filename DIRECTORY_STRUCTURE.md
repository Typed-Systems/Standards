

## Organize components using the Atomic Design

It's the approach we've adopted in [MotorK] for both our Design System and Single Page Applications. It's called: [Atomic Design].

[MotorK]: <https://www.motork.io/>
[Atomic Design]: <https://bradfrost.com/blog/post/atomic-web-design/>

### Why atomic design

Atomic design provides a clear methodology for crafting design systems. Clients and team members are able to better appreciate the concept of design systems by actually seeing the steps laid out in front of them.

Atomic design gives us the ability to traverse from abstract to concrete. Because of this, we can create systems that promote consistency and scalability while simultaneously showing things in their final context. And by assembling rather than deconstructing, we’re crafting a system right out of the gate instead of cherry picking patterns after the fact.

### Atomic Design

> Break entire interfaces down into fundamental building blocks and work up from there. That’s the basic gist of atomic design.\
> [Brad Frost]

[Brad Frost]: <https://bradfrost.com/>

The Atomic Design's principle is to split your UI parts into **small** components in order to have a better reusability.
Like chemistry, you can organize your components in `atoms`, `molecules` and `organisms`.
In addition there are also `templates` and `pages`, but we won't talk about them because we want to keep the focus on small applications' architectures.


### Atoms

Atoms are the smallest components of our application. Basically, they can be texts, buttons, form inputs and so on.
The golden rule is: if you can't split a component into smaller components then it must be an **atom**.

### Molecules
Molecules are combinations of atoms bonded together. For example, if you have `Text` and `Input` atoms, you can combine them into a `InputField` (or whatever name you want) **molecule**

### Organisms
Organisms are combinations of molecules: if you mix two or more molecules you get an **organism**.


### Folder structure

First of all we have to create our folder structure. we need to create atoms, molecules and organisms folders inside components.

- Components
  - Atoms
    - Dropdown
  - Molecules
    - Alert
    - Filter
    - Table
    - etc.
  - Organisms
    - Header
    - Form
      - Account
      - FormBuilder
      - Report
      - Team
      - User
      - etc.
    - Navigation
    - Sidebar
- Directive
- Layouts
- Pages
  - Account
  - Admin
  - Auth
  - FormBuilder
  - People
  - Report
  - Team
- Plugins
- Store




---

## Usefull Links

https://dev.to/sanfra1407/how-to-organize-your-components-using-the-atomic-design-dj3

https://uxdesign.cc/4-things-you-need-to-know-about-atomic-design-e0d3e8269420

https://www.justinmind.com/blog/atomic-design/
