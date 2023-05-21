# economy_survey_result_final
2022 Survey After Economic Lecture (age group: elementary school students) 

Composed of a total of 12 topics

Dream: Job is to find promising jobs in the future, find out our strengths, and play professional bingo games

Money: Write down your pocket money through consumption, reasonable consumption, pocket money management, and board games

Market: Market, goods and services, payment methods, market experience games
Economy: economic activities, rational choice, rational consumption, and finishing quizzes on what you learned

Finance: The type of financial company, the work done at the bank, the necessity of saving, and the concept of investment

Travel: Definition and importance of planning, information search method, scarcity, opportunity cost and sunk cost, rational choice and pocket money entry: Travel choices are also related to rational consumption in the economy

Pocket money: pocket money is the use of pocket money, planning for pocket money, rational and irrational consumption, quizzes

Metavere: The Changing World and the Fourth Industrial Revolution, the movie Ready Player One, the meaning of metaverse, metaverse type and related jobs, creating my own avatar

Rich: consumption, reasonable consumption, opportunity cost and scarcity, pocket money management, and writing down pocket money with board games

Trade: Prices in the market are determined by supply and demand, trade is, surplus and deficit, advantages of trade, rising and falling exchange rates, characteristics of Korea's trade, FTA and WTO

Culture: the meeting of culture and art, k-culture, culture and economy

Music economy: saving, bankbook sharing, saving and wasting, energy saving song

# local_children's_center_survey_result
col_name <- c("10 points", "8 points", "6 points", "4 points", "2 points")
row_name <- c("The topics covered in education were appropriate.",
              "The content of the education was easy to understand.",
              "I participated hard with interest during my education.",
              "The content of the education helped us understand the economy.",
              "I am absolutely satisfied with this training.",
              "If I get a chance next time, I want to get another education.",
              "The instructor prepared various materials for a good class.",
              "The way the class was conducted was fun and not boring.",
              "The instructor taught me well and interestingly about the economy.",
              "The training period and training time were appropriate.")


gochang_220331_dream <- data.frame(matrix(c(4,4,5,1,0,
                                            4,2,7,1,0,
                                            3,3,7,1,0,
                                            4,2,7,1,0,
                                            3,3,7,1,0,
                                            1,3,6,2,2,
                                            3,2,8,1,0,
                                            3,4,6,1,0,
                                            2,6,6,0,0,
                                            4,0,6,3,1),
                                          ncol = 5,
                                          byrow = TRUE))


colnames(gochang_220331_dream) <- col_name
rownames(gochang_220331_dream) <- row_name


gimje_220401_money <- data.frame(matrix(c(8,2,1,0,1,
                                          7,3,1,1,0,
                                          7,3,1,1,0,
                                          10,1,0,1,0,
                                          8,2,1,1,0,
                                          7,2,2,1,0,
                                          10,2,0,0,0,
                                          8,1,1,1,1,
                                          7,4,0,0,1,
                                          8,1,2,0,1),
                                        ncol = 5,
                                        byrow = TRUE))

colnames(gimje_220401_money) <- col_name
rownames(gimje_220401_money) <- row_name

jeonju_220405_market <- data.frame(matrix(c(3,1,1,0,1,
                                            3,1,1,1,0,
                                            5,1,0,0,0,
                                            2,2,2,0,0,
                                            5,0,0,0,1,
                                            4,2,0,0,0,
                                            3,0,2,0,1,
                                            4,0,0,0,2,
                                            4,2,0,0,0,
                                            3,2,1,0,0),
                                          ncol = 5,
                                          byrow = TRUE))

colnames(jeonju_220405_market) <- col_name
rownames(jeonju_220405_market) <- row_name

gimje_220405_economy <- data.frame(matrix(c(13,1,1,1,0,
                                            13,2,1,0,0,
                                            8,5,3,0,0,
                                            12,1,3,0,0,
                                            13,1,2,0,0,
                                            10,3,3,0,0,
                                            10,2,4,0,0,
                                            12,1,3,0,0,
                                            11,2,3,0,0,
                                            11,2,2,0,1),
                                          ncol = 5,
                                          byrow =TRUE))

colnames(gimje_220405_economy) <- col_name
rownames(gimje_220405_economy) <- row_name

iksan_220519_finance <- data.frame(matrix(c(7,0,1,0,0,
                                            6,0,2,0,0,
                                            5,2,1,0,0,
                                            6,1,1,0,0,
                                            7,0,1,0,0,
                                            6,1,1,0,0,
                                            5,2,1,0,0,
                                            5,1,2,0,0,
                                            6,0,1,1,0,
                                            5,2,1,0,0),
                                          ncol = 5,
                                          byrow = TRUE))

colnames(iksan_220519_finance) <- col_name
rownames(iksan_220519_finance) <- row_name

iksan_220526_market <- data.frame(matrix(c(8,0,1,0,0,
                                           7,1,1,0,0,
                                           5,2,2,0,0,
                                           7,1,1,0,0,
                                           7,1,1,0,0,
                                           7,1,1,0,0,
                                           8,0,1,0,0,
                                           4,1,4,0,0,
                                           6,1,1,1,0,
                                           6,2,1,0,0),
                                         ncol = 5,
                                         byrow = TRUE))

colnames(iksan_220526_market) <- col_name
rownames(iksan_220526_market) <- row_name

######## After classifying men and women on the questionnaire #########

jeonju_220727_market_men <- data.frame(matrix(c(3,1,2,0,0,
                                                3,2,1,0,0,
                                                2,0,2,2,0,
                                                3,1,2,0,0,
                                                3,2,1,0,0,
                                                1,2,1,2,0,
                                                2,1,3,0,0,
                                                2,2,2,0,0,
                                                1,3,2,0,0,
                                                3,0,2,0,1),
                                              ncol = 5,
                                              byrow = TRUE))
colnames(jeonju_220727_market_men) <- col_name
rownames(jeonju_220727_market_men) <- row_name

jeonju_220727_market_women <- data.frame(matrix(c(1,0,1,0,0,
                                                  1,0,1,0,0,
                                                  1,0,1,0,0,
                                                  1,0,1,0,0,
                                                  1,0,1,0,0,
                                                  0,1,1,0,0,
                                                  1,0,1,0,0,
                                                  1,0,1,0,0,
                                                  1,0,1,0,0,
                                                  1,0,1,0,0),
                                                ncol = 5,
                                                byrow = TRUE))
colnames(jeonju_220727_market_women) <- col_name
rownames(jeonju_220727_market_women) <- row_name

jeonju_220803_dream_men <- data.frame(matrix(c(2,1,1,0,0,
                                               1,2,0,0,1,
                                               3,0,0,0,1,
                                               2,1,0,0,1,
                                               3,0,0,0,1,
                                               2,1,0,0,1,
                                               2,1,0,0,1,
                                               3,0,0,0,1,
                                               2,1,0,0,1,
                                               2,0,1,0,1),
                                             ncol = 5,
                                             byrow = TRUE))
colnames(jeonju_220803_dream_men) <- col_name
rownames(jeonju_220803_dream_men) <- row_name

jeonju_220803_dream_women <- data.frame(matrix(c(2,0,0,0,0,
                                                 2,0,0,0,0,
                                                 2,0,0,0,0,
                                                 1,1,0,0,0,
                                                 2,0,0,0,0,
                                                 2,0,0,0,0,
                                                 2,0,0,0,0,
                                                 2,0,0,0,0,
                                                 2,0,0,0,0,
                                                 2,0,0,0,0),
                                               ncol = 5,
                                               byrow = TRUE))
colnames(jeonju_220803_dream_women) <- col_name
rownames(jeonju_220803_dream_women) <- row_name


jeonju_220819_market_men <- data.frame(matrix(c(3,1,1,0,0,
                                                3,1,0,1,0,
                                                2,3,0,0,0,
                                                3,2,0,0,0,
                                                2,3,0,0,0,
                                                3,1,0,1,0,
                                                4,1,0,0,0,
                                                4,0,1,0,0,
                                                3,1,1,0,0,
                                                4,0,1,0,0),
                                              ncol = 5,
                                              byrow = TRUE))

colnames(jeonju_220819_market_men) <- col_name
rownames(jeonju_220819_market_men) <- row_name

jeonju_220819_market_women <- data.frame(matrix(c(5,2,0,0,0,
                                                  3,2,2,0,0,
                                                  3,2,1,1,0,
                                                  2,1,3,1,0,
                                                  5,2,0,0,0,
                                                  3,2,0,0,2,
                                                  4,3,0,0,0,
                                                  3,1,1,1,1,
                                                  2,2,2,1,0,
                                                  4,1,1,0,1),
                                                ncol = 5,
                                                byrow = TRUE))

colnames(jeonju_220819_market_women) <- col_name
rownames(jeonju_220819_market_women) <- row_name

jeonju_220826_dream_men <- data.frame(matrix(c(5,0,1,0,0,
                                               2,3,0,1,0,
                                               5,0,1,0,0,
                                               4,2,0,0,0,
                                               4,1,1,0,0,
                                               3,2,0,1,0,
                                               4,1,1,0,0,
                                               2,3,0,1,0,
                                               2,3,1,0,0,
                                               5,0,1,0,0),
                                             ncol = 5,
                                             byrow = TRUE))

colnames(jeonju_220826_dream_men) <- col_name
rownames(jeonju_220826_dream_men) <- row_name

jeonju_220826_dream_women <- data.frame(matrix(c(3,1,1,0,0,
                                                 4,0,1,0,0,
                                                 2,2,0,1,0,
                                                 3,1,1,0,0,
                                                 3,2,0,0,0,
                                                 3,1,0,0,1,
                                                 4,0,1,0,0,
                                                 2,1,1,0,1,
                                                 1,4,0,0,0,
                                                 4,0,0,1,0),
                                               ncol = 5,
                                               byrow = TRUE))

colnames(jeonju_220826_dream_women) <- col_name
rownames(jeonju_220826_dream_women) <- row_name

# elementary_shcool_survey_results
iksan_elementary_220516_finance <- data.frame(matrix(c(11,7,3,0,0,
                                                       12,4,5,0,0,
                                                       10,4,6,1,0,
                                                       13,5,3,0,0,
                                                       7,6,3,0,0,
                                                       7,5,7,2,0,
                                                       11,6,4,0,0,
                                                       10,5,5,0,1,
                                                       12,5,5,0,1,
                                                       10,5,3,0,1
),
ncol = 5,
byrow = TRUE))

colnames(iksan_elementary_220516_finance) <- col_name
rownames(iksan_elementary_220516_finance) <- row_name

######## After classifying men and women on the questionnaire #########

jeonju_elementary_220711_travel_men <- data.frame(matrix(c(8,3,0,0,1,
                                                           7,3,1,0,1,
                                                           6,4,1,0,1,
                                                           6,4,0,1,1,
                                                           9,2,0,0,1,
                                                           6,2,3,0,1,
                                                           8,3,0,0,1,
                                                           7,4,0,0,1,
                                                           7,3,1,0,1,
                                                           7,2,2,0,1),
                                                         ncol = 5,
                                                         byrow = TRUE))


colnames(jeonju_elementary_220711_travel_men) <- col_name
rownames(jeonju_elementary_220711_travel_men) <- row_name

jeonju_elementary_220711_travel_women <- data.frame(matrix(c(11,1,0,0,0,
                                                             11,0,1,0,0,
                                                             9,1,2,0,0,
                                                             10,1,1,0,0,
                                                             10,0,2,0,0,
                                                             10,1,1,0,0,
                                                             11,1,0,0,0,
                                                             8,4,0,0,0,
                                                             11,1,0,0,0,
                                                             10,0,2,0,0),
                                                           ncol = 5,
                                                           byrow = TRUE))
colnames(jeonju_elementary_220711_travel_women) <- col_name
rownames(jeonju_elementary_220711_travel_women) <- row_name


jeonju_elementary_220713_pocketmoney_men <- data.frame(matrix(c(5,4,0,0,0,
                                                                5,2,2,0,0,
                                                                4,1,4,0,0,
                                                                6,3,0,0,0,
                                                                5,4,0,0,0,
                                                                4,3,1,1,0,
                                                                6,2,1,0,0,
                                                                4,3,2,0,0,
                                                                6,1,2,0,0,
                                                                6,3,0,0,0),
                                                              ncol = 5,
                                                              byrow = TRUE))

colnames(jeonju_elementary_220713_pocketmoney_men) <- col_name
rownames(jeonju_elementary_220713_pocketmoney_men) <- row_name

jeonju_elementary_220713_pocketmoney_women <- data.frame(matrix(c(6,2,1,1,0,
                                                                  4,3,2,1,0,
                                                                  1,4,4,1,0,
                                                                  3,3,4,0,0,
                                                                  6,1,2,1,0,
                                                                  2,3,4,1,0,
                                                                  7,3,0,0,0,
                                                                  2,2,5,1,0,
                                                                  4,4,2,0,0,
                                                                  6,3,1,0,0),
                                                                ncol = 5,
                                                                byrow = TRUE))

colnames(jeonju_elementary_220713_pocketmoney_women) <- col_name
rownames(jeonju_elementary_220713_pocketmoney_women) <- row_name

jeonju_elementary_220715_metaverse_men <- data.frame(matrix(c(10,1,0,0,0,
                                                              3,7,1,0,0,
                                                              4,2,5,0,0,
                                                              3,6,1,0,1,
                                                              9,2,0,0,0,
                                                              5,6,0,0,0,
                                                              6,4,1,0,0,
                                                              5,3,3,0,0,
                                                              7,2,1,0,1,
                                                              5,3,3,0,0),
                                                            ncol = 5,
                                                            byrow = TRUE))

colnames(jeonju_elementary_220715_metaverse_men) <- col_name
rownames(jeonju_elementary_220715_metaverse_men) <- row_name

jeonju_elementary_220715_metaverse_women <- data.frame(matrix(c(8,1,0,0,0,
                                                                5,3,1,0,0,
                                                                6,2,1,0,0,
                                                                4,4,1,0,0,
                                                                5,3,1,0,0,
                                                                4,2,3,0,0,
                                                                8,0,1,0,0,
                                                                6,2,0,1,0,
                                                                8,0,1,0,0,
                                                                5,3,1,0,0),
                                                              ncol = 5,
                                                              byrow = TRUE))
colnames(jeonju_elementary_220715_metaverse_women) <- col_name
rownames(jeonju_elementary_220715_metaverse_women) <- row_name

jeonju_elementary_220718_rich_men <- data.frame(matrix(c(4,4,4,0,0,
                                                         1,4,7,0,0,
                                                         2,4,3,2,1,
                                                         3,4,3,1,1,
                                                         4,4,3,1,0,
                                                         2,4,2,4,0,
                                                         4,2,4,1,1,
                                                         2,5,2,2,1,
                                                         3,5,2,1,1,
                                                         6,3,2,1,0),
                                                       ncol = 5,
                                                       byrow = TRUE))
colnames(jeonju_elementary_220718_rich_men) <- col_name
rownames(jeonju_elementary_220718_rich_men) <- row_name

jeonju_elementary_220718_rich_women <- data.frame(matrix(c(4,6,3,0,0,
                                                           6,5,1,1,0,
                                                           5,3,5,0,0,
                                                           8,4,1,0,0,
                                                           9,1,3,0,0,
                                                           8,5,0,1,0,
                                                           7,4,2,0,0,
                                                           4,5,3,1,0,
                                                           5,7,0,1,0,
                                                           6,2,3,1,1),
                                                         ncol = 5,
                                                         byrow = TRUE))

colnames(jeonju_elementary_220718_rich_women) <- col_name
rownames(jeonju_elementary_220718_rich_women) <- row_name


jeonju_elementary_220722_metaverse_men <- data.frame(matrix(c(3,5,3,0,0,
                                                              4,1,4,2,0,
                                                              4,4,3,0,0,
                                                              5,2,2,2,0,
                                                              8,2,1,0,0,
                                                              2,5,3,1,0,
                                                              4,4,3,0,0,
                                                              6,3,2,0,0,
                                                              6,3,2,0,0,
                                                              2,5,3,0,1),
                                                            ncol = 5,
                                                            byrow = TRUE))
colnames(jeonju_elementary_220722_metaverse_men) <- col_name
rownames(jeonju_elementary_220722_metaverse_men) <- row_name

jeonju_elementary_220722_metaverse_women <- data.frame(matrix(c(5,2,1,0,0,
                                                                3,3,2,0,0,
                                                                4,3,1,0,0,
                                                                5,2,1,0,0,
                                                                6,2,0,0,0,
                                                                5,1,2,0,0,
                                                                7,1,0,0,0,
                                                                4,3,1,0,0,
                                                                6,2,0,0,0,
                                                                3,4,0,1,0),
                                                              ncol = 5,
                                                              byrow = TRUE))

colnames(jeonju_elementary_220722_metaverse_women) <- col_name
rownames(jeonju_elementary_220722_metaverse_women) <- row_name



jeonju_elementary_220722_travel_men <- data.frame(matrix(c(8,2,1,0,0,
                                                           6,4,1,0,0,
                                                           5,4,1,1,0,
                                                           8,1,2,0,0,
                                                           5,4,2,0,0,
                                                           4,4,3,0,0,
                                                           6,2,3,0,0,
                                                           5,4,1,1,0,
                                                           5,5,1,0,0,
                                                           6,1,4,0,0),
                                                         ncol = 5,
                                                         byrow = TRUE))


colnames(jeonju_elementary_220722_travel_men) <- col_name
rownames(jeonju_elementary_220722_travel_men) <- row_name


jeonju_elementary_220722_travel_women <- data.frame(matrix(c(6,2,0,0,0,
                                                             5,3,0,0,0,
                                                             5,2,1,0,0,
                                                             7,1,0,0,0,
                                                             6,2,0,0,0,
                                                             5,3,0,0,0,
                                                             5,3,0,0,0,
                                                             4,4,0,0,0,
                                                             6,2,0,0,0,
                                                             5,1,1,1,0),
                                                           ncol = 5,
                                                           byrow = TRUE))



colnames(jeonju_elementary_220722_travel_women) <- col_name
rownames(jeonju_elementary_220722_travel_women) <- row_name

muju_elementary_220730_market_men <- data.frame(matrix(c(2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0,
                                                         2,2,0,0,0),
                                                       ncol = 5,
                                                       byrow = TRUE))

colnames(muju_elementary_220730_market_men) <- col_name
rownames(muju_elementary_220730_market_men) <- row_name

muju_elementary_220730_market_women <- data.frame(matrix(c(1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0,
                                                           1,0,0,0,0),
                                                         ncol = 5,
                                                         byrow = TRUE))
colnames(muju_elementary_220730_market_women) <- col_name
rownames(muju_elementary_220730_market_women) <- row_name

jeonju_elementary_220830_trade_men <- data.frame(matrix(c(7,1,2,0,0,
                                                          7,3,0,0,0,
                                                          7,1,1,1,0,
                                                          8,0,2,0,0,
                                                          8,0,2,0,0,
                                                          7,1,1,1,0,
                                                          8,1,1,0,0,
                                                          7,1,2,0,0,
                                                          8,1,1,0,0,
                                                          8,1,0,1,0),
                                                        ncol = 5,
                                                        byrow = TRUE))

colnames(jeonju_elementary_220830_trade_men) <- col_name
rownames(jeonju_elementary_220830_trade_men) <- row_name

jeonju_elementary_220830_trade_women <- data.frame(matrix(c(9,1,0,1,0,
                                                            6,3,1,0,1,
                                                            6,2,2,1,0,
                                                            8,0,3,0,0,
                                                            5,4,2,0,0,
                                                            4,5,2,0,0,
                                                            9,1,0,1,0,
                                                            8,1,1,1,0,
                                                            7,1,3,0,0,
                                                            5,4,2,0,0),
                                                          ncol = 5,
                                                          byrow = TRUE))

colnames(jeonju_elementary_220830_trade_women) <- col_name
rownames(jeonju_elementary_220830_trade_women) <- row_name

jeonju_elementary_220902_trade_men <- data.frame(matrix(c(10,3,0,0,0,
                                                          7,3,2,1,0,
                                                          6,4,3,0,0,
                                                          9,2,2,0,0,
                                                          9,2,2,0,0,
                                                          7,2,4,0,0,
                                                          10,3,0,0,0,
                                                          7,3,2,1,0,
                                                          8,3,1,0,1,
                                                          9,2,2,0,0),
                                                        ncol = 5,
                                                        byrow = TRUE))


colnames(jeonju_elementary_220902_trade_men) <- col_name
rownames(jeonju_elementary_220902_trade_men) <- row_name

jeonju_elementary_220902_trade_women <- data.frame(matrix(c(6,4,2,0,0,
                                                            4,5,3,0,0,
                                                            5,0,6,1,0,
                                                            8,2,1,1,0,
                                                            8,2,1,1,0,
                                                            6,5,0,0,1,
                                                            8,3,1,0,0,
                                                            5,4,4,4,4,
                                                            6,3,3,0,0,
                                                            6,3,1,2,0),
                                                          ncol = 5,
                                                          byrow = TRUE))
colnames(jeonju_elementary_220902_trade_women) <- col_name
rownames(jeonju_elementary_220902_trade_women) <- row_name

jeonju_elementary_220905_culutre_men <- data.frame(matrix(c(6,3,0,0,0,
                                                            6,3,0,0,0,
                                                            5,2,1,1,0,
                                                            2,5,2,0,0,
                                                            3,3,2,1,0,
                                                            1,4,3,0,1,
                                                            4,5,0,0,0,
                                                            4,3,1,0,1,
                                                            4,4,1,0,0,
                                                            3,3,2,0,1),
                                                          ncol = 5,
                                                          byrow = TRUE))


colnames(jeonju_elementary_220905_culutre_men) <- col_name
rownames(jeonju_elementary_220905_culutre_men) <- row_name

jeonju_elementary_220905_culture_women <- data.frame(matrix(c(1,3,0,0,0,
                                                              2,2,0,0,0,
                                                              1,3,0,0,0,
                                                              1,3,0,0,0,
                                                              2,2,0,0,0,
                                                              2,1,1,0,0,
                                                              3,1,0,0,0,
                                                              2,2,0,0,0,
                                                              2,2,0,0,0,
                                                              1,3,0,0,0),
                                                            ncol = 5,
                                                            byrow = TRUE))

colnames(jeonju_elementary_220905_culture_women) <- col_name
rownames(jeonju_elementary_220905_culture_women) <- row_name

iksan_elementary_220907_rich_men <- data.frame(matrix(c(10,3,0,0,0,
                                                        9,4,0,0,0,
                                                        7,4,2,0,0,
                                                        11,0,2,0,0,
                                                        12,1,0,0,0,
                                                        8,3,1,1,0,
                                                        9,4,0,0,0,
                                                        7,4,2,0,0,
                                                        9,4,0,0,0,
                                                        12,0,0,1,0),
                                                      ncol = 5,
                                                      byrow = TRUE))
colnames(iksan_elementary_220907_rich_men) <- col_name
rownames(iksan_elementary_220907_rich_men) <- row_name


iksan_elementary_220907_rich_women <- data.frame(matrix(c(7,2,0,0,0,
                                                          7,1,1,0,0,
                                                          6,3,0,0,0,
                                                          8,1,0,0,0,
                                                          6,1,1,0,0,
                                                          7,2,1,0,0,
                                                          9,0,0,0,0,
                                                          7,2,0,0,0,
                                                          8,1,0,0,0,
                                                          7,1,1,0,0),
                                                        ncol = 5,
                                                        byrow = TRUE))
colnames(iksan_elementary_220907_rich_women) <- col_name
rownames(iksan_elementary_220907_rich_women) <- row_name

gunsan_elementary_220923_musiceconmy_men <- data.frame(matrix(c(8,1,3,0,0,
                                                                8,3,1,0,0,
                                                                6,4,2,0,0,
                                                                10,1,1,0,0,
                                                                10,2,0,0,0,
                                                                8,2,2,0,0,
                                                                9,0,3,0,0,
                                                                8,4,0,0,0,
                                                                8,3,1,0,0,
                                                                7,3,2,0,0),
                                                              ncol = 5,
                                                              byrow = TRUE))
colnames(gunsan_elementary_220923_musiceconmy_men) <- col_name
rownames(gunsan_elementary_220923_musiceconmy_men) <- row_name


gunsan_elementary_220923_musiceconmy_women <- data.frame(matrix(c(6,2,1,0,0,
                                                                  7,2,0,0,0,
                                                                  5,3,1,0,0,
                                                                  7,2,0,0,0,
                                                                  6,3,0,0,0,
                                                                  4,4,1,0,0,
                                                                  6,2,1,0,0,
                                                                  5,4,0,0,0,
                                                                  7,1,1,0,0,
                                                                  4,4,1,0,0),
                                                                ncol = 5,
                                                                byrow = TRUE))
colnames(gunsan_elementary_220923_musiceconmy_women) <- col_name
rownames(gunsan_elementary_220923_musiceconmy_women) <- row_name


gunsan_elementary_220923_2_musiceconmy_men <- data.frame(matrix(c(7,4,0,0,0,
                                                                  9,2,0,0,0,
                                                                  6,4,1,0,0,
                                                                  7,3,1,0,0,
                                                                  8,2,1,0,0,
                                                                  4,6,1,0,0,
                                                                  8,3,0,0,0,
                                                                  6,5,0,0,0,
                                                                  6,5,0,0,0,
                                                                  8,3,0,0,0),
                                                                ncol = 5,
                                                                byrow = TRUE))
colnames(gunsan_elementary_220923_2_musiceconmy_men) <- col_name
rownames(gunsan_elementary_220923_2_musiceconmy_men) <- row_name


gunsan_elementary_220923_2_musiceconmy_women <- data.frame(matrix(c(5,3,1,0,0,
                                                                    7,2,0,0,0,
                                                                    6,1,2,0,0,
                                                                    4,5,0,0,0,
                                                                    7,2,0,0,0,
                                                                    7,0,2,0,0,
                                                                    6,3,0,0,0,
                                                                    6,2,1,0,0,
                                                                    6,2,1,0,0,
                                                                    3,5,1,0,0),
                                                                  ncol = 5,
                                                                  byrow = TRUE))

colnames(gunsan_elementary_220923_2_musiceconmy_women) <- col_name
rownames(gunsan_elementary_220923_2_musiceconmy_women) <- row_name



jeonju_elementary_220926_culture_men <- data.frame(matrix(c(3,6,2,0,1,
                                                            4,3,4,0,1,
                                                            3,3,5,0,1,
                                                            2,5,4,0,1,
                                                            4,4,3,0,1,
                                                            3,4,4,0,1,
                                                            7,2,2,0,1,
                                                            3,5,3,0,1,
                                                            4,5,2,0,1,
                                                            3,5,3,0,1),
                                                          ncol = 5,
                                                          byrow = TRUE))
colnames(jeonju_elementary_220926_culture_men) <- col_name
rownames(jeonju_elementary_220926_culture_men) <- row_name

jeonju_elementary_220926_culture_women <- data.frame(matrix(c(5,3,2,0,0,
                                                              5,5,1,0,0,
                                                              5,3,2,1,0,
                                                              5,3,3,0,0,
                                                              3,3,2,1,0,
                                                              6,2,2,1,0,
                                                              7,3,0,1,0,
                                                              4,4,2,0,1,
                                                              8,1,1,1,0,
                                                              6,3,1,1,0),
                                                            ncol = 5,
                                                            byrow = TRUE))
colnames(jeonju_elementary_220926_culture_women) <- col_name
rownames(jeonju_elementary_220926_culture_women) <- row_name

jeonju_elementary_221012_rich_men <- data.frame(matrix(c(6,6,2,0,0,
                                                         5,6,3,0,0,
                                                         5,2,6,1,0,
                                                         4,5,5,0,0,
                                                         5,6,1,1,0,
                                                         2,9,3,0,0,
                                                         5,5,4,0,0,
                                                         4,5,3,2,0,
                                                         4,7,3,0,0,
                                                         5,1,5,2,1),
                                                       ncol = 5,
                                                       byrow = TRUE))

colnames(jeonju_elementary_221012_rich_men) <- col_name
rownames(jeonju_elementary_221012_rich_men) <- row_name

jeonju_elementary_221012_rich_women <- data.frame(matrix(c(5,4,4,0,0,
                                                           5,5,3,0,0,
                                                           5,3,4,1,0,
                                                           6,4,3,0,0,
                                                           3,7,3,0,0,
                                                           5,3,3,2,0,
                                                           8,2,3,0,0,
                                                           4,5,3,1,0,
                                                           5,3,4,1,0,
                                                           2,5,4,2,0),
                                                         ncol = 5,
                                                         byrow = TRUE))
colnames(jeonju_elementary_221012_rich_women) <- col_name
rownames(jeonju_elementary_221012_rich_women) <- row_name


## Tie up data frames by topic
dream <- data.frame(rbind(gochang_220331_dream,
      jeonju_220803_dream_men,
      jeonju_220803_dream_women,
      jeonju_220826_dream_men,
      jeonju_220826_dream_women
      ))

dream_sum <- colSums(dream)


money <- gimje_220401_money

money_sum <- colSums(money)


market <- data.frame(rbind(jeonju_220727_market_men,
                           jeonju_220727_market_women,
                           jeonju_220819_market_men,
                           jeonju_220819_market_women,
                           muju_elementary_220730_market_men,
                           muju_elementary_220730_market_women))

market_sum <- colSums(market)

economy <- gimje_220405_economy

economy_sum <- colSums(economy)

finance <- data.frame(rbind(iksan_220519_finance,
                            iksan_elementary_220516_finance
                            ))

finance_sum <- colSums(finance)

travel <- data.frame(rbind(jeonju_elementary_220711_travel_men,
                           jeonju_elementary_220711_travel_women,
                           jeonju_elementary_220722_travel_men,
                           jeonju_elementary_220722_travel_women))

travel_sum <- colSums(travel)

pocket_monety <- data.frame(rbind(jeonju_elementary_220713_pocketmoney_men,
                                  jeonju_elementary_220713_pocketmoney_women))

pocket_monety_sum <- colSums(pocket_monety)

metaverse <- data.frame(rbind(jeonju_elementary_220715_metaverse_men,
                              jeonju_elementary_220715_metaverse_women,
                              jeonju_elementary_220722_metaverse_men,
                              jeonju_elementary_220722_metaverse_women))

metaverse_sum <- colSums(metaverse)

rich <- data.frame(rbind(jeonju_elementary_220718_rich_men,
                         jeonju_elementary_220718_rich_women,
                         iksan_elementary_220907_rich_men,
                         iksan_elementary_220907_rich_women,
                         jeonju_elementary_221012_rich_men,
                         jeonju_elementary_221012_rich_women))
rich_sum <- colSums(rich)

trade <- data.frame(rbind(jeonju_elementary_220830_trade_men,
                          jeonju_elementary_220830_trade_women,
                          jeonju_elementary_220902_trade_men,
                          jeonju_elementary_220902_trade_women
                          ))

trade_sum <- colSums(trade) 

culture <- data.frame(rbind(jeonju_elementary_220905_culutre_men,
                            jeonju_elementary_220905_culture_women,
                            jeonju_elementary_220926_culture_men,
                            jeonju_elementary_220926_culture_women))

culture_sum <- colSums(culture)

music_economy <- data.frame(rbind(gunsan_elementary_220923_musiceconmy_men,
                                  gunsan_elementary_220923_musiceconmy_women,
                                  gunsan_elementary_220923_2_musiceconmy_men,
                                  gunsan_elementary_220923_2_musiceconmy_women))


music_economy_sum <- colSums(music_economy)

### Tie up data frames by gender

men <- data.frame(rbind(jeonju_220727_market_men,
                        jeonju_220803_dream_men,
                        jeonju_220819_market_men,
                        jeonju_220826_dream_men,
                        jeonju_elementary_220711_travel_men,
                        jeonju_elementary_220713_pocketmoney_men,
                        jeonju_elementary_220715_metaverse_men,
                        jeonju_elementary_220718_rich_men,
                        jeonju_elementary_220722_metaverse_men,
                        jeonju_elementary_220722_metaverse_men,
                        muju_elementary_220730_market_men,
                        jeonju_elementary_220830_trade_men,
                        jeonju_elementary_220902_trade_men,
                        jeonju_elementary_220905_culutre_men,
                        iksan_elementary_220907_rich_men,
                        gunsan_elementary_220923_musiceconmy_men,
                        gunsan_elementary_220923_2_musiceconmy_men,
                        jeonju_elementary_220926_culture_men,
                        jeonju_elementary_221012_rich_men))

men_sum <- colSums(men)

women <- data.frame(rbind(jeonju_220727_market_women,
                          jeonju_220803_dream_women,
                          jeonju_220819_market_women,
                          jeonju_220826_dream_women,
                          jeonju_elementary_220711_travel_women,
                          jeonju_elementary_220713_pocketmoney_women,
                          jeonju_elementary_220715_metaverse_women,
                          jeonju_elementary_220718_rich_women,
                          jeonju_elementary_220722_metaverse_women,
                          jeonju_elementary_220722_metaverse_women,
                          muju_elementary_220730_market_women,
                          jeonju_elementary_220830_trade_women,
                          jeonju_elementary_220902_trade_women,
                          jeonju_elementary_220905_culture_women,
                          iksan_elementary_220907_rich_women,
                          gunsan_elementary_220923_musiceconmy_women,
                          gunsan_elementary_220923_2_musiceconmy_women,
                          jeonju_elementary_220926_culture_women,
                          jeonju_elementary_221012_rich_women))
women_sum <- colSums(women)

### Data frame grouping based on local children's centers and elementary schools

local_children_center <- data.frame(rbind(gochang_220331_dream,
                                          gimje_220401_money,
                                          jeonju_220405_market,
                                          gimje_220405_economy,
                                          iksan_220519_finance,
                                          iksan_220526_market,
                                          jeonju_220727_market_men,
                                          jeonju_220727_market_women,
                                          jeonju_220803_dream_men,
                                          jeonju_220803_dream_women,
                                          jeonju_220819_market_men,
                                          jeonju_220819_market_women,
                                          jeonju_220826_dream_men,
                                          jeonju_220826_dream_women
                                          ))
local_children_center_sum <- colSums(local_children_center)

elementary_school <- data.frame(rbind(iksan_elementary_220516_finance,
                                      jeonju_elementary_220711_travel_men,
                                      jeonju_elementary_220711_travel_women,
                                      jeonju_elementary_220713_pocketmoney_men,
                                      jeonju_elementary_220713_pocketmoney_women,
                                      jeonju_elementary_220715_metaverse_men,
                                      jeonju_elementary_220715_metaverse_women,
                                      jeonju_elementary_220718_rich_men,
                                      jeonju_elementary_220718_rich_women,
                                      jeonju_elementary_220722_metaverse_men,
                                      jeonju_elementary_220722_metaverse_women,
                                      jeonju_elementary_220722_travel_men,
                                      jeonju_elementary_220722_travel_women,
                                      muju_elementary_220730_market_men,
                                      muju_elementary_220730_market_women,
                                      jeonju_elementary_220830_trade_men,
                                      jeonju_elementary_220830_trade_women,
                                      jeonju_elementary_220902_trade_men,
                                      jeonju_elementary_220902_trade_women,
                                      jeonju_elementary_220905_culutre_men,
                                      jeonju_elementary_220905_culture_women,
                                      iksan_elementary_220907_rich_men,
                                      iksan_elementary_220907_rich_women,
                                      gunsan_elementary_220923_musiceconmy_men,
                                      gunsan_elementary_220923_musiceconmy_women,
                                      gunsan_elementary_220923_2_musiceconmy_men,
                                      gunsan_elementary_220923_2_musiceconmy_women,
                                      jeonju_elementary_220926_culture_men,
                                      jeonju_elementary_220926_culture_women,
                                      jeonju_elementary_221012_rich_men,
                                      jeonju_elementary_221012_rich_women))

elementary_school_sum <- colSums(elementary_school)
