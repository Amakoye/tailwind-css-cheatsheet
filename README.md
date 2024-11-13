# Tailwind CSS Utility Classes Cheatsheet

## Table of Contents
- [Layout](#layout)
  - [Display](#display)
  - [Flexbox](#flexbox)
  - [Grid](#grid)
- [Spacing](#spacing)
  - [Margin](#margin)
  - [Padding](#padding)
- [Typography](#typography)
  - [Font Size](#font-size)
  - [Font Weight](#font-weight)
  - [Text Alignment](#text-alignment)
  - [Text Color](#text-color)
- [Backgrounds](#backgrounds)
  - [Background Color](#background-color)
  - [Background Size](#background-size)
  - [Background Position](#background-position)
- [Borders](#borders)
  - [Border Width](#border-width)
  - [Border Color](#border-color)
  - [Border Radius](#border-radius)
- [Effects](#effects)
  - [Opacity](#opacity)
  - [Box Shadow](#box-shadow)
- [Interactivity](#interactivity)
  - [Cursor](#cursor)
  - [User Select](#user-select)
  - [Hover/Focus States](#hoverfocus-states)
- [Responsive Design](#responsive-design)
  - [Breakpoints](#breakpoints)
- [Color System](#color-system)
- [Tips & Best Practices](#tips--best-practices)

## Layout

### Display
- `block` - Block element
- `inline` - Inline element
- `inline-block` - Inline-block element
- `flex` - Flex container
- `inline-flex` - Inline flex container
- `grid` - Grid container
- `hidden` - Hide element

### Flexbox
- `flex-row` - Direction: left to right
- `flex-col` - Direction: top to bottom
- `flex-wrap` - Allow wrapping
- `flex-nowrap` - Prevent wrapping
- `justify-start` - Justify: start
- `justify-end` - Justify: end
- `justify-center` - Justify: center
- `justify-between` - Justify: space between
- `items-start` - Align items: start
- `items-center` - Align items: center
- `items-end` - Align items: end

### Grid
- `grid-cols-{1-12}` - Number of columns
- `gap-{size}` - Gap between grid items
- `col-span-{1-12}` - Column span
- `row-span-{1-6}` - Row span

[↑ Back to top](#table-of-contents)

## Spacing

### Margin
- `m-{size}` - All sides
- `mt-{size}` - Top
- `mr-{size}` - Right
- `mb-{size}` - Bottom
- `ml-{size}` - Left
- `mx-{size}` - Horizontal
- `my-{size}` - Vertical

### Padding
- `p-{size}` - All sides
- `pt-{size}` - Top
- `pr-{size}` - Right
- `pb-{size}` - Bottom
- `pl-{size}` - Left
- `px-{size}` - Horizontal
- `py-{size}` - Vertical

*Size values: 0, 0.5, 1, 1.5, 2, 2.5, 3, 3.5, 4, 5, 6, 7, 8, 9, 10, 11, 12, 14, 16, 20, 24, 28, 32, 36, 40, 44, 48, 52, 56, 60, 64, 72, 80, 96*

[↑ Back to top](#table-of-contents)

## Typography

### Font Size
- `text-xs` - 0.75rem
- `text-sm` - 0.875rem
- `text-base` - 1rem
- `text-lg` - 1.125rem
- `text-xl` - 1.25rem
- `text-2xl` - 1.5rem
- `text-3xl` - 1.875rem
- `text-4xl` - 2.25rem
- `text-5xl` - 3rem

### Font Weight
- `font-thin` - 100
- `font-extralight` - 200
- `font-light` - 300
- `font-normal` - 400
- `font-medium` - 500
- `font-semibold` - 600
- `font-bold` - 700
- `font-extrabold` - 800
- `font-black` - 900

### Text Alignment
- `text-left` - Left align
- `text-center` - Center align
- `text-right` - Right align
- `text-justify` - Justify text

### Text Color
- `text-{color}-{shade}` - Text color
- Example: `text-blue-500`, `text-red-700`

[↑ Back to top](#table-of-contents)

## Backgrounds

### Background Color
- `bg-{color}-{shade}` - Background color
- Example: `bg-gray-100`, `bg-blue-500`

### Background Size
- `bg-auto` - Auto size
- `bg-cover` - Cover
- `bg-contain` - Contain

### Background Position
- `bg-center` - Center
- `bg-top` - Top
- `bg-bottom` - Bottom
- `bg-left` - Left
- `bg-right` - Right

[↑ Back to top](#table-of-contents)

## Borders

### Border Width
- `border` - 1px
- `border-0` - 0px
- `border-2` - 2px
- `border-4` - 4px
- `border-8` - 8px

### Border Color
- `border-{color}-{shade}` - Border color
- Example: `border-gray-200`, `border-blue-500`

### Border Radius
- `rounded` - 0.25rem
- `rounded-sm` - 0.125rem
- `rounded-md` - 0.375rem
- `rounded-lg` - 0.5rem
- `rounded-xl` - 0.75rem
- `rounded-2xl` - 1rem
- `rounded-full` - 9999px

[↑ Back to top](#table-of-contents)

## Effects

### Opacity
- `opacity-0` - 0
- `opacity-25` - 0.25
- `opacity-50` - 0.5
- `opacity-75` - 0.75
- `opacity-100` - 1

### Box Shadow
- `shadow-sm` - Small
- `shadow` - Default
- `shadow-md` - Medium
- `shadow-lg` - Large
- `shadow-xl` - Extra large
- `shadow-2xl` - 2x extra large
- `shadow-none` - None

[↑ Back to top](#table-of-contents)

## Interactivity

### Cursor
- `cursor-pointer` - Pointer
- `cursor-default` - Default
- `cursor-not-allowed` - Not allowed

### User Select
- `select-none` - Prevent selection
- `select-text` - Allow selection
- `select-all` - Select all

### Hover/Focus States
- Add `hover:` or `focus:` prefix to any utility
- Example: `hover:bg-blue-700`, `focus:outline-none`

[↑ Back to top](#table-of-contents)

## Responsive Design

### Breakpoints
- `sm:` - 640px
- `md:` - 768px
- `lg:` - 1024px
- `xl:` - 1280px
- `2xl:` - 1536px

Example: `md:flex-col` will apply flex-col at medium screens and above

[↑ Back to top](#table-of-contents)

## Color System
Available colors with their shade variants (50-900):
- `gray`
- `red`
- `yellow`
- `green`
- `blue`
- `indigo`
- `purple`
- `pink`

Shade values:
- 50 (lightest)
- 100
- 200
- 300
- 400
- 500
- 600
- 700
- 800
- 900 (darkest)

[↑ Back to top](#table-of-contents)

## Tips & Best Practices
1. **Combining Utilities**
   ```html
   <div class="flex items-center justify-between p-4 bg-blue-500 text-white">
   ```

2. **Responsive Design**
   ```html
   <div class="w-full md:w-1/2 lg:w-1/3">
   ```

3. **State Variants**
   ```html
   <button class="bg-blue-500 hover:bg-blue-700 focus:outline-none">
   ```

4. **Custom Values**
   ```html
   <div class="top-[117px]">
   ```

5. **Organization**
   - Group related utilities together
   - Put responsive utilities last
   - Keep hover/focus states near their base utilities

[↑ Back to top](#table-of-contents)
