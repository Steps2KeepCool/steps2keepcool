---
title: Home
---

Keeping the Earth livable for human society needs us to move together towards a low-carbon world.
We need to take action in the different roles that people take on in our lives, at multiple levels within society: voter, elected official, business person, individual, and all the others.

This site aims to bring together useful resources on steps on the path to a stable climate.

<script>

// Event handlers for each element with class expand

function doExpandCss_42343(evt) {	
//  alert("doExpandCss_42343(evt)");

  // Called when clicking the main list item the first time, as set by element attribute
  // We are now handling this in a <span> in the <li>
  // Go up one to the <ul> then get 2nd child element (the child <ul> of nested list)
  // find first child item, then set the style to show it
  var childUlNode = evt.currentTarget.parentElement.children[1];
  childUlNode.classList.toggle("open");

  // Toggle class on current node to "open"
  evt.currentTarget.classList.toggle("open");

  // Set event-based handler via property
  evt.currentTarget.onclick = doCloseCss_42343;

  // Avoid event bubbling further and expanding/collapsing other nodes
  evt.cancelBubble = true;
}

function doCloseCss_42343(evt) {
//  alert("doCloseCss_42343() called!");

  // Called when clicking the main list item
  // find first child item, then set the style to hide it
  var childUlNode = evt.currentTarget.parentElement.children[1];
  childUlNode.classList.toggle("open");

  // Toggle class on current node to "open"
  evt.currentTarget.classList.toggle("open");

  // Set event-based handler programmatically
  evt.currentTarget.onclick = doExpandCss_42343;

  // Avoid event bubbling further and expanding/collapsing other nodes
  evt.cancelBubble = true;
}

</script>


<div id="styleDiv42343" >
  <style>
    #styleDiv42343 ul.top { list-style-type: none; }
    #styleDiv42343 li.top { margin: 10px; padding: 5px; }
    #styleDiv42343 span.top { background: #60ff60; margin: 10px; padding: 5px;}
    #styleDiv42343 ul.sub { display: none; margin-top: 10px; }
    #styleDiv42343 li.expand::before { content: "+ "; }
    #styleDiv42343 li.expand::after { content: "  CLICK THIS"; }
    #styleDiv42343 span.expand::before { content: "+ "; }
    #styleDiv42343 span.expand::after { content: "  CLICK THIS"; }
    #styleDiv42343 span.open::before { content: "- "; }
    #styleDiv42343 span.open::after { content: ""; }
    #styleDiv42343 ul.open { display: block; margin-top: 10px; }
  </style>
  <ul class="top">
    <li class="top"><span class="top expand">If you live in a country where you can vote...</span>
      <ul class="sub">
        <li>*** VOTE!!! for candidates who recognize the climate crisis and will act.
        </li>
        <li>National, state, county, local city and town - all are important!
        </li>
      </ul>
    </li>
    <li class="top"><span class="top expand">If you are in government...</span>
      <ul class="sub">
        <li>Talk to others & establish who is also concerned, to work together; start a weekly meeting about the climate crisis and next steps to take together. (<a href='http://katharinehayhoe.com'>Prof. Katharine Hayhoe</a> is a climate scientist and communicator with great advice on how to talk with others on the subject.)
        </li>
        <li>Publicize your concern for the climate crisis.
        </li>
        <li>Talk to climate-concerned citizen groups and businesses in your constituency.  See what their concerns are, and what their ideas are.
        </li>
        <li>Pursue systemic policies to incentivize reduction in GHG emissions (e.g. in US, <a href='https://citizensclimatelobby.org/'>Citizens' Climate Lobby</a> ).
        </li>
        <li>Start finding out where your constituency generates GHGs (transport, industry, power, agriculture, housing) and see how to cut emissions in half over next decade.
        </li>
        <li>Some areas to look at reducing GHGs, where applicable:
      <ul>
        <li>if communities are economically dependent on fossil fuel extraction, see what alternatives would be possible right now, to ensure a just transition away from fossil fuels.
        </li>
        <li>transport: prioritizing mass transit, especially electric (including electric buses), electric taxis and ride-hailing cars/buses. Where possible and appropriate, encourage e-bike, cycling, and walkable city planning.
        </li>
        <li>buildings: avoid natural gas in new buildings. Encourage electric induction cooking, heat pump heating/cooling, and buildings efficiency programs such as insulation and lighting.
        </li>
        <li>help to streamline processes for connection of GHG-free electrical generation & storage to the power grid.
        </li>
        <li>ease permitting and use of community solar & wind, as well as household solar and storage.
        </li>
        <li>encourage use of electric vehicles with charging networks, and building codes aiding installation of charging stations.
        </li>
        <li>move fleet vehicles (national, local, municipal) over to low-GHG emission vehicles (e.g. electric delivery and maintenance vehicles, electric refuse trucks).
        </li>
      </ul>
        </li>
        <li>For more information:
      <ul>
        <li><a href='https://exponentialroadmap.org/'>The Exponential Roadmap: Scaling 36 Solutions to Halve Emissions by 2030</a>
        </li>
        <li><a href='https://www.drawdown.org/'>Project Drawdown</a>
        </li>
      </ul>
        </li>
      </ul>
    </li>
    <li class="top"><span class="top expand">If you are in a business or organization...</span>
      <ul class="sub">
        <li>Talk to other people in your organization, area or industry, and share your concerns. Start a discussion group, and share ideas. (<a href='http://katharinehayhoe.com'>Prof. Katharine Hayhoe</a> is a climate scientist and communicator with great advice on how to talk with others.)
        </li>
        <li>Find out how the organization causes GHG emissions (even if rough). Start evaluating how to cut them. Start weekly meetings to kick start discussions, then monitor progress.
        </li>
        <li>Ask other members of the organization about ideas to reduce GHGs.
        </li>
        <li>Use banks and retirement fund providers which avoid lending to and investments in fossil fuel extraction companies.
        </li>
        <li>Work to establish internal policies to support GHG reduction.
        </li>
        <li>See how being a low-GHG business can be a market differentiator.
        </li>
        <li>If possible and comfortable to do so, ask people higher up in the organization as well to see what their thoughts are on climate and how to reduce GHGs.
        </li>
        <li>Possible areas to consider, as applicable:
      <ul>
        <li>replace gas-fueled vehicles with electric vehicles (including buses, trucks, company cars)
        </li>
        <li>where possible, avoid flying or driving for meetings, & use vidconf or calls with document sharing instead (this may be more feasible after an initial in-person meeting to establish rapport)
        </li>
        <li>look at supply chains for reductions (including shipping, air freight)
        </li>
        <li>ensure any current methane gas infrastructure is not leaking
        </li>
        <li>look into how to transition away from use of methane for industrial processes, building heating or cooking in the next few years (towards electric infrastructure such as heat pumps, electric induction stoves)
        </li>
        <li>for construction projects, use CO2-sequestered concrete and low-GHG materials
        </li>
        <li>if possible, depending on circumstances and job, see if working from home for 1 day a week is feasible
        </li>
      </ul>
        </li>
        <li>For more information:
      <ul>
        <li><a href='https://exponentialroadmap.org/'>The Exponential Roadmap: Scaling 36 Solutions to Halve Emissions by 2030</a>
        </li>
        <li><a href='https://www.drawdown.org/'>Project Drawdown</a>
        </li>
      </ul>
        </li>
      </ul>
    </li>
    <li class="top"><span class="top expand">For specific kinds of business, organization, art, agriculture...</span>
      <ul class="sub">
        <li>The music world:
      <ul>
        <li><a href='https://musicdeclares.net/#actions'>Music Declares Emergency - Actions</a> .
        </li>
        <li><a href='https://www.feat.ltd/'>FEAT.</a> Australian artists and others investing in solar.
        </li>
      </ul>
        </li>
        <li>Construction and built environment - architects, building service engineers, civil engineers, structural engineers, or related: <a href='https://constructiondeclares.com/'>Construction Declares...</a> .
        </li>
        <li>Food and agriculture:
      <ul>
        <li><a href='https://www.drawdown.org/solutions/food'>Project Drawdown - Food</a> .
        </li>
        <li><a href='https://www.wri.org/our-work/topics/food'>World Resources Institute - Food</a> .
        </li>
      </ul>
        </li>
        <li>Looking for funding for clean technology projects : <a href='https://cleantechcapital.club/'>Cleantech Capital Club</a> .
        </li>
      </ul>
    </li>
    <li class="top"><span class="top expand">As a person...</span>
      <ul class="sub">
        <li>*** VOTE for candidates who recognize the climate crisis and will act.
        </li>
        <li>Support national climate-concerned groups promoting climate policy (e.g. in US, <a href='https://citizensclimatelobby.org/'>Citizens' Climate Lobby</a>).
        </li>
        <li>Support local climate-concerned groups.
        </li>
        <li>Talk to others around you as the opportunity arises about the climate crisis, and encourage them to support action. (<a href='http://katharinehayhoe.com'>Prof. Katharine Hayhoe</a> is a climate scientist and communicator with great advice on how to talk with others.)
        </li>
        <li>See what the local town, city or county council is doing to reduce GHG emissions in your area, and suggest places where they can improve - mass transit, electric buses (including school buses where used), electric refuse trucks, housing regulations, car-lite town areas, community solar/wind programs.
        </li>
        <li>If you have a bank account, ask your bank whether they lend to fossil fuel extraction companies, and tell them you are opposed to this. Consider changing to a bank which does not lend to fossil fuel extraction companies.
        </li>
        <li>If you have retirement/pension account, ask your provider whether they invest in fossil fuel extraction companies, and tell them you are opposed to this. Consider changing your fund to one which does not invest in fossil fuel extraction companies.
        </li>
        <li>Today see what parts of a lifestyle of the future make sense for you:
      <ul>
        <li>Avoid the hassle of driving without waiting for driverless cars - try taking mass transit if it's available, or an electric taxi or electric ride-hailing vehicle.
        </li>
        <li>If you are a car driver, look at an electric car for the next purchase or lease (or if appropriate, consider whether alternatives to having a car will work)
        </li>
        <li>If you fly frequently, try avoiding the time waiting and hassle of delayed flights, and consider lower-GHG alternatives.
        </li>
        <li>If you have a house, cut your bills by insulating, enjoy cleaner indoor air by moving away from gas appliances (try an electric induction stove).
        </li>
        <li>If you have a lawn/yard, use an electric mower and tools, not gas (or consider different landscaping and skip the mowing!).
        </li>
        <li>Depending on circumstances, try replacing a beef or lamb meal every now and again, and see how you feel.
        </li>
      </ul>
        </li>
        <li>For more information:
      <ul>
        <li><a href='https://exponentialroadmap.org/'>The Exponential Roadmap: Scaling 36 Solutions to Halve Emissions by 2030</a>
        </li>
        <li><a href='https://www.drawdown.org/'>Project Drawdown</a>
        </li>
      </ul>
        </li>
      </ul>
    </li>
  </ul>
</div>


<script>

// Autofind the unique style-wrapper div
var myStyleDiv_42343 = document.getElementById("styleDiv42343");
var myExpandElements_42343 = myStyleDiv_42343.getElementsByClassName("expand");
var i_42343;

for( i_42343 = 0; i_42343 < myExpandElements_42343.length; i_42343++ ) {
  myExpandElements_42343[i_42343].onclick = doExpandCss_42343;
}

</script>


