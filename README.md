# testing-jest-rtl-Bonnie-Schulkin
https://www.udemy.com/course/react-testing-library/learn/lecture/24418712#overview


# Screen query methods
command[all]byQueryType

### command
- get: expect element to be in DOM
- query: expect element not to be in DOM
- find: expect element to appear async

### [All]
- (exclude) expect only one match
- (include) expect more than one match

### QueryType
- Role (preferred) - accessibility
- AltText (images)
- Text (display elements)
- Form elements
- - PlaceholderText
- - LabelText
- - DisplayValue

### Tips
- Use getBy when you know it will be on screen
- Use queryBy when it will be null, using incorrect one will fail the tes

### User Event
- All methods and promises must be awaited

### Avoid
- Test ids, user would not interact with these
- FireEvent, prefer userEvent as its more appropriate towards real user interaction

#### Testing library cheat sheet (React)
https://testing-library.com/docs/react-testing-library/cheatsheet/

#### Query priority
https://testing-library.com/docs/queries/about/#priority

#### Testing library API
https://testing-library.com/docs/queries/about/