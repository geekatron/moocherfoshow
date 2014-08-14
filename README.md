moocherfoshow
=============

Moocher Fo' Sure

1. Navigate to http://potfarmmoocherpro.com/
2. Open Console via Developer Tools
3. Use the following command depending on intended prize pickup:
  *  To claim rally prizes: $('.rally-entry').each(function(i, el) { retrieveReward($(el), 'rally'); });
  *  To claim feed prizes: $('.feed-entry').each(function(i, el) { retrieveReward($(el), 'wall'); });
