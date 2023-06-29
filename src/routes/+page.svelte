<script>
  import App from "../App.svelte";
  import HtmlTag from "../component/htmlTag.svelte";
  import ArrayAndObject from "../component/Reactivity/arrayAndObject.svelte";
  import DecleringProps from "../component/Props/DecleringProps.svelte";
  import IfBlock from "../component/Logic/IfBlock.svelte";
  import SpreadProps from "../component/Props/SpreadProps.svelte";
  import Each from "../component/Logic/Each.svelte";
  import Keyed from "../component/Logic/Keyed.svelte";

  const pkg = {
    name: "svelte",
    speed: "blazing",
    version: 4,
    website: "https://svelte.dev",
  };
</script>

<App />
<HtmlTag />
<ArrayAndObject />
<DecleringProps answer={25} />
<SpreadProps {...pkg} />
<IfBlock />
<Each />
<Keyed />
