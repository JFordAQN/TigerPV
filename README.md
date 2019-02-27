# TigerPV is a SAS-based tool for evaluating acqusitions NPV/account at Tiger. The tool focuses primarily on direct mail accounts, though there are underlying curves in the tool for other segments that can be leveraged for other acqusitions valuations.

# Run PV Calc takes an input driver table for which we have pulled actual account performance data (using # Pull Perf) and assigns predicted driver curve values to each account in the driver table, based on their segmentation.

# Agg Summary then creates an aggregated table, for use in exporting to excel to perform level adjustments. Those level adjustments are fed back to the tool to yield a adjusted predicted curves and final NPV valuation, which can be exported to excel for use in a waterfall view.
