``` YAML

1. Define Component:
   - Name: Counter
   - Props: none

2. Import Dependencies:
   - React
   - useState

3. Set Component State:
   - count: 0

4. Define Event Handlers:
   - increment: increase count by 1
   - decrement: decrease count by 1

5. Implement Helper Functions: none

6. Render Component:
   - Display count value
   - Display "Increment" button with onClick handler for increment
   - Display "Decrement" button with onClick handler for decrement

7. Export Component:
   - Export Counter component




- Component:
    name: Counter
    props: none
- Dependencies:
    - React
    - useState
- State:
    - count: 0
- EventHandlers:
    - increment:
        action: increase count by 1
    - decrement:
        action: decrease count by 1
- HelperFunctions: none
- Render:
    - Display:
        - count value
        - Increment button:
            onClick: increment
        - Decrement button:
            onClick: decrement
- Export: Counter

Component Recipe: Counter

Ingredients:
- React
- useState

Instructions:

1. Prepare the component:
   - Name: Counter
   - Props: none

2. Gather dependencies:
   - Import React
   - Import useState

3. Prepare state:
   - Mix count with initial value 0

4. Create event handlers:
   - Stir increment function to increase count by 1
   - Stir decrement function to decrease count by 1

5. No helper functions required

6. Assemble the component:
   - Display count value
   - Add Increment button with onClick action: increment
   - Add Decrement button with onClick action: decrement
   

7. Serve the Counter component by exporting it
    
    ``` YAML
// 'use client'

// // Your task is to implement the filterItems
// // function to filter the items array based on the searchQuery string.
// // The function should return a new array of filtered items that match the search query.
// // The search should be case-insensitive and match on both the name and description properties of each item.
// // The function should also handle the case where the search query is empty (i.e. return all the items).
// import React, { useState } from 'react'

// interface Item {
//   id: number
//   name: string
//   description: string
// }

// interface ItemListProps {
//   items: Item[]
// }

// const ItemList: React.FC<ItemListProps> = ({ items }) => {
//   const [searchQuery, setSearchQuery] = useState('')

//   const handleSearch = (event: React.ChangeEvent<HTMLInputElement>) => {
//     setSearchQuery(event.target.value)
//   }

//   const filteredItems = filterItems(items, searchQuery)

//   return (
//     <div>
//       <input type="text" value={searchQuery} onChange={handleSearch} />
//       <ul>
//         {filteredItems.map((item) => (
//           <li key={item.id}>
//             <h2>{item.name}</h2>
//             <p>{item.description}</p>
//           </li>
//         ))}
//       </ul>
//     </div>
//   )
// }

// const filterItems = (items: Item[], searchQuery: string): Item[] => {
//   return items.filter(
//     (item) =>
//       item.name.toLowerCase().includes(searchQuery.toLowerCase()) ||
//       item.description.toLowerCase().includes(searchQuery.toLowerCase())
//   );
// };

// export default ItemList
