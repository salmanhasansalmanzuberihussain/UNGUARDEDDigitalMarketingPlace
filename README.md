   1.NPX create-next-app@latest unguardeddigitalmarketing  

    Next App is one of the most advanced technologies   

  

2. Typescript, ESLint, Tailwindcss, Src, App Router   

Typescript is JavaScript strongly typed programmed language that builds on JavaScript giving you better tooling   

ESLint is a static code analysis tool for identifying problematic patterns found in JavaScript code  

App Router introduces a new model for building applications using React's latest  

  

3. Add Yarn Dev  

  

4. NPX ShadCN-UI@latest init  

Component library for Next App   

  

5. Typescript – Yes  

     Style- Default  

     Color-Slate  

     Global CSS- Src/Globals.css  

     CSS Variables- Yes  

     Tailwind.config.js-   

     Components- @/components  

     Utils- @/lib/utils  

     Yes  

     Components. Json - Yes  

  

6. ClassName=’h-full’  

Classname adds the styled font needed for CSS styling  

  

7. Relative h-full font-sans antialiased  

  

  

8. Cn(“relative h-full font-sans antialized”), inter.className)  

All the fonts will have the className with inter  

  

9. Main className=’’"specifies the main content of a document”  

  

  

10. Utils.ts  

  

  

11. Relative flex flex-col min-h-screen  

  

  

12. Components [MaxWidthWrapper.tsx] (add a component maxwidthwrapper)  

  

  

13. Import {ReactNode} from “react”  

  

  

ReactNode is a type that represents a react element 

  

14.Const MaxWidthWrapper = {{ReactNode is a type that represents a React element}}  

  

  

15.ClassName, Children and add className?: string, children: ReactNode  

This component will keep the component within the boundries.   

  

  

16. Use a shadcn template and copy and paste tailwind css to customize code  

  

  

17.Add textfont to page.tsx and the necessary text to the text  

  

  

18.mt-6 text-lg max-w-prose text-muted-foreground [Css files to create proper styling]  

These tailwind properties there is no reason to memorize. Its more important to just have a general idea and research and adjust when real changes need to be made.  

  

  

19.Add a link href tag. A link href tag is a Link that sends someone to a component file in your project.  

  

  

20.NPX shadcn-ui@latest add button  

  

21. Add button variant &rarr 

  

22.  Grid grid-cols-1 gap-y-12 sm:grid-cols-2 lg:grid-cols-3 lg:gap-x-8 

Grid adds a certain amount of space between columns 

  

23. Add MaxWidthWrapper className=’py-20’ 

  

24.Yarn add lucide-react 

  

25.Create a perks.map and key={perks.name} etc... 

  

This perks.map creates a name in instant delivery 

  

26. Add Navigation Bar to the website 

  

27.For Div className and header and maxwidthwrapper and div div and add <Link href=’/’> 

  

28.Add Section className=’border-t border-gray-200 bg-gray-50'> 

  

29. Add the Icons.tsx in the components file that has a bunch of paths and icons 

  

30. Add Icons.logo className=’h-10 w-10' 

  

31. Config and add index.ts 
 
32. Import Button from ‘./ui/button’ 
 
33.Add button and add specific stying for the button 
 
34.Add NavItemProps and add specific category 
35. Add Category and add typeof PRODUCT_CATEGORIES[number] 
 
36.categroy:Category, handleOpen: () => void, isOpen:boolean, isAnyOpen:boolean 
 
37.Const Navitem =({isAnyOpen, category, handleopen,isOpen} :NavItemProps) 

38.{category.label} 
 
39.onClick={handleOpen} 
Opens the navbar with categories 
 
Adding navitemprops and adding category handleOpen and isOpen and isAnyOpen boolean creates a component that can be used for Navitem 
 
Variant changes the color of the button and category label adds the button 
 
40.Chevron Down is a component that is a bottom button  
 
41.Add the active items into NavItem 
 
42.Add the specific divs and add the specific categories NavItem.tsx and use mapping to add the relative items needed 
 
43.Add Image src={item.imageSrc} alt=’products category image’, fill className=’object-cover object-center 
 
44.Link href=item.href className=”mt-6 block font-medium> and add item.name

45.Add the template for Use-on-click-outside.ts. The useeffect helps perform side effects 
 
46.User Sign in with Link href 

47. Add a npx shadcn-ui@latest add sheet

48. Import {Sheet} from './ui/sheet' ("use client")

49. const itemCount =0

50.Make necessary css and file changes for Cart.tsx

51.Add yarn add express which is a backend server and then from there make sure to impprt server.ts

52. get-payload.ts import dotenv from "dotenv"

53.

	 






 
