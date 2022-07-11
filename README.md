# UFO Data Repository

## Project Overview
While small in scope, this project is enormous in importance! Extraterrestrials may be walking around as imposters among us, and hopefully this quick reference database will help prove it! In order to better centralize data on UFO incidents - thus allowing for easier access by interested parties - we've developed a small webapp capable of displaying all known UFO sightings, as well as a large amount of data pertaining to them. This data, to allow faster, more convenient data recovery, is able to be organized and filtered by a variety of factors. Ideally, anybody with a passing interest, a curious mind, or a UFO experience of their own should be able to rapidly find and learn about any UFO sighting they want.

## Results
While using this webapp, an individual can utilize the five search criteria on the left side of the page in order to stratify the data displayed on the right side of the page. Each of these filters is an HTML form, with functionality added through JS, which can be combined and mixed together in any combination a user may desire when stratifying by multiple criteria. The criteria we support filtering for are: Date, City, State, Country, and Shape. 

## Summary
One notable drawback of this "architecture" is that our entire database is contained as a local, bespoke javascript object which we must curate and add to if we ever wish to expand our data set. One major recommendation for the future that we suggest is to add a "UFO Sighting" submission form to the site, through which a user can describe their UFO sighting, and provide any additional relevant informaiton. This submission form could then be approved or rejected (so as to account for malicious actors) by the site owner, and approved submissions appended to the JS object.
