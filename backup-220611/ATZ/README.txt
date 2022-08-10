// looks good but need to toggle source for longs & shorts
ATZ's ATR2 indicator source seems a bit strange
I would like it to be high+ATR above and low-ATR below
But can only select one of these at a time

// no need to toggle source for longs & shorts
TrailingStopLoss does do high+ATR above and low-ATR below
But broken now (and its mutiplier steps was too big)
I fixed this (TrailingStopLoss2)

// validate
Can match ATZ and TrailingStopLoss2 indicators by
1) setting source to low on ATZ and compare with TrailingStopLoss
2) setting source to high on ATZ and compare with TrailingStopLoss


