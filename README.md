# customer-reward-points
if (data.purchaseValue >= 50 && data.purchaseValue < 100) {
        const difference = data.purchaseValue - 50;
        pointsFor50DollarsPurchase = difference * 1;
      }

      if (data.purchaseValue > 100) {
        const difference = data.purchaseValue - 100;
        pointsFor100DollarsPurchase = difference * 2;
      }

      // To calculate total points for a particular month
      totalPointsForTheMonth =
        pointsFor50DollarsPurchase + pointsFor100DollarsPurchase;
changes...
