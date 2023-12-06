# Burger_King
In early July, Burger King caused a stir in Thailand with the launch of a new offering: a burger with no meat and 20 slices of cheese, referred to as "the real cheeseburger." Later that month, Burger King Brazil celebrated the release of the Barbie movie with a special Barbie meal. This meal included a cheeseburger dressed with smoky pink sauce, a side of Ken's potatoes, and a pink vanilla strawberry milkshake, accompanied by a pink frosted donut for dessert.

**While the viral marketing strategy is clear, we can't help but wonder what data supported the decision to invest in such different burgers.**

Aligning your strategy with what the numbers show is a task intrinsically loaded with uncertainty. The right answer to "how much are we going to make from this" is a million-dollar question (or in Burger King's case, a few billion). And yet, we would need to at least have a rough idea of the neighborhood in which we may land. Will it be 500k, 1MM, 500MM? Having realistic expectations can help you decide if it will be a good investment or not. This is where market sizing comes into play.

**Market sizing is an exercise in which you try to estimate the total size of the market by logically thinking through the elements that make up revenue. In its simplest form, it will be the quantity you sell multiplied by the price.**

By breaking down each element into a few key variables, we end up with an overall structure of the market size logic for a potential new Whopper. Making some assumptions, we can build our base case, a reasonable scenario. I am assuming that a single BK restaurant will be open for 12 hours per day (from 10:00 to 22:00), with 4 hours being peak hours (2 for lunch and 2 for dinner). Given the wide variety of flavors available, we would sell at least 1 burger during off-peak hours, but a maximum of 3 during busier hours. Adding this up, we get around 20 new Whoppers sold per day, which equates to approximately 6 million Whoppers per year, considering all 907 current Burger King restaurants in Brazil. Assuming they each sell for R$ 35.00 (as a combo), we arrive at our base case of R$ 222 million per year in gross revenue.

If we are comfortable with these estimates, this would be an informed guide on what to expect. However, we are not considering the uncertainty and risks embedded in these numbers.

**After all, the market is dynamic!**

Burger prices may need to be adjusted to stay competitive, or the marketing campaign's success may lead to higher sales during peak hours. The premises must not be static numbers but rather a range (e.g., I would likely sell between 2–5 Whoppers per hour during peak hours).

To account for these possibilities, we will conduct a Monte-Carlo simulation, which is essentially a method of running a series of random experiments. In this simulation, we use 100,000 different scenarios, each with different assumptions (e.g., for one scenario, we use a price of 15 and assume the restaurant is open 347 days a year; in another, the price is 20, and the restaurant is open 352 days a year).

Based on these assumptions, we can estimate that yearly revenues for our new whopper will likely fall between R$ 99 million and R$ 352 million, with the most likely figure being around ~R$ 200 million per year.
Once we consider fixed costs (e.g., rent and employees) and variable costs (e.g., ingredients and delivery), we can estimate the likelihood of Burger King making a profit or a loss based on these assumptions. This approach provides a much more comprehensive way to think about market sizes than solely relying on the base case.

Additionally, we can gain insight into the most important variables considering the uncertainty in our assumptions.

Intuitively, the greater the variability in price, the greater the variability in market size. In other words, the greater the uncertainty we have about the price at which we will sell our new Whopper, the higher the risk of our investment, followed by how many Whoppers we sell during off-peak hours, peak hours, and so on.

And there you have it! This is just an initial approach to how this fast-food giant can make a decision on whether or not to launch a new Whopper and how we can estimate its potential success.

