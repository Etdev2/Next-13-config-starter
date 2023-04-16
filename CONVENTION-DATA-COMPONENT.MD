``` Yaml

- Component:
    name: UserList
    props:
      - title: string
- Dependencies:
    - React
    - useState
    - useEffect
    - Supabase client
- State:
    - users: []
    - loading: true
- EventHandlers: none
- HelperFunctions:
    - fetchUsers:
        action: fetch users from Supabase
- Render:
    - Display:
        - title (prop)
        - Loading message if loading state is true
        - User list if loading state is false
- Export: UserList


Component Recipe: UserList

Ingredients:
- React
- useState
- useEffect
- Supabase client
- Props:
  - title: string

Instructions:

1. Prepare the component:
   - Name: UserList
   - Props: title

2. Gather dependencies:
   - Import React
   - Import useState
   - Import useEffect
   - Import Supabase client

3. Prepare state:
   - Mix users with initial value empty array
   - Mix loading with initial value true

4. No event handlers required

5. Create helper functions:
   - Stir fetchUsers function to fetch users from Supabase

6. Assemble the component:
   - Display title prop
   - Add Loading message if loading state is true
   - Add User list if loading state is false
   - Use useEffect to call fetchUsers when the component mounts

7. Serve the UserList component by exporting it
``` Yaml