# Reading

## [Context API](https://reactjs.org/docs/context.html)

1. What can React Context provide your app?
  - It can help by providing a way to pass data through the component tree without having to pass props down manually at every level.
2. Why might we use Context?
  - Context is primarily used when some data needs to be accessible by many components at the different nesting levels.  
3. Why should we use it sparingly?
  - it makes components reuse more difficult. 

## [Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

1. Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:
    - Takeaway 1: Theme toggle with the use of context api is a cool tool and could be used in many different ways, either in styling or showing more dynamic interaction for users in a app, and much more.
    - Takeaway 2: [with-context](https://github.com/SunHuawei/with-context) pretty cool resourse showing how to style many leaf's or endpoints by linking the theme to the branch.
       import { withContext } from "with-context";

      export const ThemeContext = React.createContext("light");
      export const withTheme = withContext(ThemeContext, "theme");

      import { withTheme } from "./withTheme";
      import { styles } from "../consts";

    @withTheme
      export default class LeafComponent extends React.PureComponent {
        render() {
          const { theme } = this.props;
        return (
            <div style={styles[theme]}>LeafComponent with theme: {theme}</div>
          );
        }
      }

## Additional Questions

1. Looking ahead at this module’s course schedule, What do you look forward to learning?
  - Anything that will stick to my skill set. Help me better understand react and make it more useful on my skill base!
2. What are your learning goals after reading and reviewing the class README?
  - Reading today's reading it looks like theres a lot coming up and I hope I can understand react further and make it my own this upcoming weeks.