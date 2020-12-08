Story splitting cheat sheet
============================

## Criteria for good stories: **INVEST**

* **I**ndependent
  * Stories must be independent of each other. There should be no dependency relationships or context relationships if possible.
* **N**egotiable
  * Stories must be negotiable. Stories are tools for conversation and are not necessarily final. They are sometimes amended during later reviews. 
* **V**aluable
  * Stories must have value for the client.
* **E**stimable
  * An estimate must be possible. They must be small enough and specific enough to estimate the time that is required.
* **S**mall
  * Stories must be small enough for the team to handle by themselves (at minimum, they must be small enough to fit in one sprint). They must be split into small enough units.
* **T**estable
  * Acceptance criteria must be clearly defined.

## Story splitting format

* ### Splitting according to steps in the workflow

 * #### Example story

    It is possible for content managers to post articles on the corporate website.

 * #### Example of how to split the story
   * It is possible to directly post articles on the corporate website.
   * It is possible to post articles following a review by an editor.
   * It is possible to post articles following a review by the legal affairs department.

* ### Splitting according to variations of operational rules

 * #### Example story

    It is possible for users to search for flight reservations with flexible dates.

 * #### Example of how to split the story

   * It is possible to search in the format "n days from x to y".
   * It is possible to search in the format "weekends in December".
   * It is possible to search in the format "n days before and after x and y".

* ### Splitting by separating important initiatives from other work

 * #### Example story

    It is possible for users to pay for flights using JCB, VISA, MasterCard, Diners Club or AMEX.

 * #### Example of how to split the story

   * It is possible to make payments using JCB, VISA, MasterCard, Diners Club or AMEX.
   * It is possible to make payments using JCB, VISA, MasterCard, Diners Club and AMEX.

* ### Splitting by separating simple tasks from complex ones

 * #### Example story

    It is possible for users to search for flights between two destinations.

 * #### Example of how to split the story

   * It is possible to set a maximum number of layovers.
   * It is possible to include nearby airports.

* ### Splitting by data variation

 * #### Example story

    It is possible for content managers to create articles.

 * #### Example of how to split the story

   * In Japanese.
   * In English.

* ### Splitting by data input method

 * #### Example story

    It is possible for users to search for flights between two destinations.

 * #### Example of how to split the story

   * With a simple date format (yyyyMMdd).
   * With rich calendar UI.

* ### Delaying response to performance

 * #### Example story

    It is possible for users to search for flights between two destinations.

 * #### Example of how to split the story

   * Searching is slow but possible. “Searching” is displayed until the search is completed.
   * Searching can be done within five seconds.

* ### Splitting by processing method (e.g. CRUD)

 * #### Example story

    It is possible for users to manage their own account.

 * #### Example of how to split the story

   * It is possible to sign up.
   * It is possible to update account settings.
   * It is possible to terminate accounts.

* ### Splitting by technical verification or investigation

 * #### Example story

    It is possible for users to pay by credit card.

 * #### Example of how to split the story

   * Credit card processing is investigated.
   * Credit card processing is implemented.


----


Source: http://xp123.com/articles/invest-in-good-stories-and-smart-tasks/
