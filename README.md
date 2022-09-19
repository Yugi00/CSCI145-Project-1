# CSCI145-Project-1

## Task 1, Part 1:

```
    ~/project1$ python3 main.py --data=data/small.csv.gz --verbose
    DEBUG:root:computing indices
    DEBUG:root:computing values
    DEBUG:root:i=0 residual=0.0
    INFO:root:rank=0 pagerank=4.0825e-01 url=5
    INFO:root:rank=1 pagerank=4.0825e-01 url=6
    INFO:root:rank=2 pagerank=4.0825e-01 url=4
    INFO:root:rank=3 pagerank=4.0825e-01 url=1
    INFO:root:rank=4 pagerank=4.0825e-01 url=3
    INFO:root:rank=5 pagerank=4.0825e-01 url=2
```

## Task 1, Part 2:

```
    ~/project1$ python3 main.py --data=data/lawfareblog.csv.gz --search_query='corona'
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/britains-coronavirus-response
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/european-elections-time-coronavirus
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/trump-right-britain-handling-coronavirus-well
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/brexit-not-immune-coronavirus
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/coronavirus-death-toll-rises-above-200-experts-expect-it-spread
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/coronavirus-infection-rates-rise-us-china-curbs-viruss-spread-justice-department-charges-two-chinese
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/china-responds-coronavirus-iron-grip-information-flow
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/beijing-turns-public-diplomacy-and-messaging-campaigns-coronavirus-spreads-worldwide
```

```
    ~/project1$ python3 main.py --data=data/lawfareblog.csv.gz --search_query='trump'
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/trump-right-britain-handling-coronavirus-well
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/breaking-down-trumps-middle-east-policy
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/blessing-hidden-trumps-unesco-withdrawal
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/mercurial-presidency-trump-and-governing-crisis
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/guantanamo-habeas-motion-appears-reference-trump-tweet
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/body-double-what-medieval-executive-theory-tells-us-about-trumps-twitter-accounts
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/sovereignty-steroids-international-institutions-and-trump-administrations-ideology-patriotism
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/trump-administration-throws-down-gauntlet-icc-court-should-decline-challenge
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/trump-moves-cut-irans-oil-revenues-whats-his-endgame
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/can-coindinistas-save-iraq-trump
```

```
    ~/project1$ python3 main.py --data=data/lawfareblog.csv.gz --search_query='iran'
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/breaking-news-nsa-spied-iran
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/iraq-and-enduring-conflict-between-united-states-and-iran
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/trump-moves-cut-irans-oil-revenues-whats-his-endgame
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/thoughts-icjs-decision-iran-v-united-states-and-trump-administrations-treaty-withdrawals
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/state-department-affirms-iran-deal-only-political-commitment
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/comprehensive-timeline-iran-deal
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/britain-rejects-us-request-use-uk-bases-nuclear-standoff-iran
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/brookings-debate-how-should-congress-vote-iran-nuclear-deal
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/backlash-kurdish-independence-referendum-begins-trump-has-made-decision-iran-deal-russian-and-us
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/attacking-irans-cultural-sites-would-violate-hague-cultural-property-convention
```

*Was unable to figure out why all the tests came out the same.

## Task 1, Part 3:

```
    ~/project1$ python3 main.py --data=data/lawfareblog.csv.gz
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaugh-judicial-lamb-national-security
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/uks-high-court-rules-prime-ministers-government-may-not-unilaterally-trigger-article-50
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/brexecution-hard-brexit
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/doj-oig-report-use-section-215
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/odnis-2016-transparency-report-summary
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/director-national-intelligence-releases-2016-transparency-report
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/odni-releases-three-fisc-opinions
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-internet
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-failure-acknowledge-changes-communications-technology-implications-privacy
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/how-free-brexit-and-movement-peoples
```

```
    ~/project1$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaugh-judicial-lamb-national-security
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/uks-high-court-rules-prime-ministers-government-may-not-unilaterally-trigger-article-50
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/brexecution-hard-brexit
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/doj-oig-report-use-section-215
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/odnis-2016-transparency-report-summary
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/director-national-intelligence-releases-2016-transparency-report
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/odni-releases-three-fisc-opinions
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-internet
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-failure-acknowledge-changes-communications-technology-implications-privacy
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/how-free-brexit-and-movement-peoples
```

*Was unable to figure out why both tests came out to be the same.

## Task 1, Part 4:

```
    ~/project1$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose 
    DEBUG:root:computing indices
    DEBUG:root:computing values
    DEBUG:root:i=0 residual=0.0
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaugh-judicial-lamb-national-security
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/uks-high-court-rules-prime-ministers-government-may-not-unilaterally-trigger-article-50
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/brexecution-hard-brexit
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/doj-oig-report-use-section-215
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/odnis-2016-transparency-report-summary
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/director-national-intelligence-releases-2016-transparency-report
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/odni-releases-three-fisc-opinions
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-internet
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-failure-acknowledge-changes-communications-technology-implications-privacy
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/how-free-brexit-and-movement-peoples
```

```
    ~/project1$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --alpha=0.99999
    DEBUG:root:computing indices
    DEBUG:root:computing values
    DEBUG:root:i=0 residual=0.0
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaugh-judicial-lamb-national-security
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/uks-high-court-rules-prime-ministers-government-may-not-unilaterally-trigger-article-50
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/brexecution-hard-brexit
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/doj-oig-report-use-section-215
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/odnis-2016-transparency-report-summary
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/director-national-intelligence-releases-2016-transparency-report
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/odni-releases-three-fisc-opinions
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-internet
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-failure-acknowledge-changes-communications-technology-implications-privacy
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/how-free-brexit-and-movement-peoples
```

```
    ~/project1$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2
    DEBUG:root:computing indices
    DEBUG:root:computing values
    DEBUG:root:i=0 residual=0.0
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaugh-judicial-lamb-national-security
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/uks-high-court-rules-prime-ministers-government-may-not-unilaterally-trigger-article-50
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/brexecution-hard-brexit
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/doj-oig-report-use-section-215
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/odnis-2016-transparency-report-summary
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/director-national-intelligence-releases-2016-transparency-report
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/odni-releases-three-fisc-opinions
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-internet
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-failure-acknowledge-changes-communications-technology-implications-privacy
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/how-free-brexit-and-movement-peoples
```

```
    ~/project1$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2 --alpha=0.99999
    DEBUG:root:computing indices
    DEBUG:root:computing values
    DEBUG:root:i=0 residual=0.0
    INFO:root:rank=0 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaugh-judicial-lamb-national-security
    INFO:root:rank=1 pagerank=7.7009e-03 url=www.lawfareblog.com/uks-high-court-rules-prime-ministers-government-may-not-unilaterally-trigger-article-50
    INFO:root:rank=2 pagerank=7.7009e-03 url=www.lawfareblog.com/brexecution-hard-brexit
    INFO:root:rank=3 pagerank=7.7009e-03 url=www.lawfareblog.com/doj-oig-report-use-section-215
    INFO:root:rank=4 pagerank=7.7009e-03 url=www.lawfareblog.com/odnis-2016-transparency-report-summary
    INFO:root:rank=5 pagerank=7.7009e-03 url=www.lawfareblog.com/director-national-intelligence-releases-2016-transparency-report
    INFO:root:rank=6 pagerank=7.7009e-03 url=www.lawfareblog.com/odni-releases-three-fisc-opinions
    INFO:root:rank=7 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-internet
    INFO:root:rank=8 pagerank=7.7009e-03 url=www.lawfareblog.com/brett-kavanaughs-failure-acknowledge-changes-communications-technology-implications-privacy
    INFO:root:rank=9 pagerank=7.7009e-03 url=www.lawfareblog.com/how-free-brexit-and-movement-peoples
```

## Task 2, Part 1:

```
    ~/project1$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
    Traceback (most recent call last):
      File "pagerank.py", line 252, in <module>
        v = g.make_personalization_vector(args.personalization_vector_query)
      File "pagerank.py", line 109, in make_personalization_vector
        url = self._index_to_url(index)
      File "pagerank.py", line 90, in _index_to_url
        return self.index_dict[index]
    KeyError: tensor(0.)
```

## Task 2, Part 2

```
    ~/project1$  python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona' --search_query='-corona'
    Traceback (most recent call last):
      File "pagerank.py", line 252, in <module>
        v = g.make_personalization_vector(args.personalization_vector_query)
      File "pagerank.py", line 109, in make_personalization_vector
        url = self._index_to_url(index)
      File "pagerank.py", line 90, in _index_to_url
        return self.index_dict[index]
    KeyError: tensor(0.)
```
