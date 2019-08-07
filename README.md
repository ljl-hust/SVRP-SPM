# SVRP-SPM
The instances of SVRP-SPM
There exist three sets of SVRP-SPM instances (RD01,RD02,RD03) and the generatd method of each set is detialed by our paper. For a set of instances, the number of customer can be {10, 20, 30, 40, 50, 60, 70}, the working capacity of vehicle can be {5, 6, 7, 8} and the maximun limited number of time windows can be {1, 2, 3}. In fact, the working capacity of housekeeper is acutally 8 hours, and each customer maybe has 1 to 3 time windows. But for our experiments, the working capacity and the maximun limited number of time windows can be set by our code easily. If the maximun limited number of time windows is 2, we only select the former two time windows for testing. Each instance is named as RDxxNyy, where xx represents the instance type and yy is the the number of customer. For example, RD01N20 denotes the instance of
type RD01 which has 20 customers. There are the following attributes in instance text:

CUST NO.-------The mark number of customer(including depot, number 0 repersents depot).
XCOORD.-------The geographical longitude of customers and depot.
YCOORD.-------The geographical latitude of  customers and depot.
DEMAND.-------The demand of customers(including depot, setting the demand of depot to be 0).
TWNUM.-------The actual number of time windows(including depot, depot has only one time window).
TWS.-------Time windows of customers and depot.
