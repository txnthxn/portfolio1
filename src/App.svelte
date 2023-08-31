<script>
  import { Router, Route } from "svelte-routing";
  import Sidebar from "./components/Sidebar.svelte";
  import About from "./routes/about/about.svelte";
  import Contact from "./routes/contact/contact.svelte";
  import Home from "./routes/home/home.svelte";
  import Projects from "./routes/projects/projects.svelte";
</script>

<main>
  <Router>
    <Route path="/" component={Home} />
    <Route path="/about" component={About} />
    <Route path="/projects" component={Projects} />
    <Route path="/contact" component={Contact} />
  </Router>
  <div>
    <Sidebar />
  </div>
</main>
