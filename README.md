# 🚀 Bitcoin OKX Loan Strategy Dashboard

Real-time monitoring dashboard for achieving 1 Bitcoin via modified recursive leverage strategy.

## 📊 Quick Links
- **[Live Dashboard](https://zudin2007.github.io/btc-okx-loan-strategy/)** - Interactive tracker
- **[Strategy Guide](docs/STRATEGY_GUIDE.md)** - Complete documentation

## ✨ Features

- 📈 Real-time portfolio metrics (value, LTV, progress)
- ⚠️ Smart LTV safety alerts with color coding
- 🎯 Milestone tracking (0.25, 0.5, 0.75, 1.0 BTC)
- 💾 Persistent data storage (LocalStorage)
- 📱 Fully responsive design (desktop & mobile)
- 📥 Export/Import functionality
- 🔐 Secure (no server, all calculations local)

## 🎯 Strategy Overview

**Target:** 1.0 Bitcoin  
**Timeline:** ~20 months  
**Method:** Modified recursive leverage via OKX  
**Risk Level:** Medium (manageable)  
**Max LTV:** 55% (safety threshold)

### Key Phases:
1. **Month 0:** Borrow $20K → Buy 0.286 BTC (Total: 0.458 BTC)
2. **Month 6:** BTC @ $95K → Borrow $15K more (Total: 0.616 BTC)
3. **Month 12:** BTC @ $120K → Borrow $10K more (Total: 0.699 BTC)
4. **Month 20:** Reach 1.0 BTC target! 🎉

## 📱 How to Use Dashboard

1. **Visit:** https://zudin2007.github.io/btc-okx-loan-strategy/
2. **Monthly Update:**
   - Current BTC price (check OKX/exchange)
   - Your BTC quantity (check OKX wallet)
   - Total debt (check OKX lending)
   - Months elapsed (since start)
3. **Click:** "Update Dashboard"
4. **Monitor:** LTV ratio (keep < 55%)
5. **Export:** Data backup anytime

## 📊 Metrics Explained

| Metric | Meaning | Healthy Range |
|--------|---------|---------------|
| **Portfolio Value** | Your BTC × Current Price | Growing |
| **LTV Ratio** | Total Debt / Collateral Value | < 55% |
| **Progress** | Your BTC / 1.0 target | Increasing |
| **Interest Accrued** | 9% APY on loans | Minimize |

## 🚨 Safety Alerts

- 🟢 **GREEN (LTV < 45%):** Excellent - 35% crash buffer
- 🔵 **BLUE (LTV 45-55%):** Safe - 25% crash buffer  
- 🟡 **YELLOW (LTV 55-65%):** Caution - Monitor weekly
- 🔴 **RED (LTV > 65%):** Danger - Liquidation risk!

## 📖 Full Strategy Guide

See **[docs/STRATEGY_GUIDE.md](docs/STRATEGY_GUIDE.md)** for:
- Detailed timeline & milestones
- Financial projections & breakdowns
- Risk management protocols
- Price predictions 2026-2030
- FAQ & troubleshooting
- Quick reference tables

## 🔐 Security & Privacy

✅ **Secure:**
- No data sent to servers
- All calculations local (browser-only)
- No API keys or credentials stored
- No login required

⚠️ **Usage Notes:**
- Data persists in browser LocalStorage
- Clear history if using shared computer
- Export/backup data monthly
- Use private/incognito for sensitive updates

## 📊 Example Usage

**Scenario:** Month 6 (Q4 2026) - BTC at $95K

1. Open dashboard
2. Input:
   - Current Price: 95,000
   - Your BTC: 0.616
   - Total Debt: 35,000
   - Months: 6
3. Dashboard shows:
   - Portfolio: $58,520
   - LTV: 59.8% (caution)
   - Progress: 61.6% (halfway!)
   - Action: Consider Loan #2

## 📅 Recommended Schedule

- **Weekly:** Check LTV ratio (no action usually needed)
- **Monthly:** Update all metrics in dashboard
- **Quarterly:** Deep review & rebalancing
- **At key prices:** 
  - BTC $95K → Evaluate Loan #2
  - BTC $120K → Evaluate Loan #3
  - BTC $150K+ → Final push to 1 BTC

## 🎯 Milestones

- [ ] 0.25 BTC (Milestone 1) - Month 3
- [ ] 0.50 BTC (Milestone 2) - Month 6
- [ ] 0.75 BTC (Milestone 3) - Month 12
- [ ] 1.00 BTC (TARGET!) - Month 20 🚀

## ⚠️ Disclaimer

This dashboard is for **personal tracking only**. 

- ❌ NOT financial advice
- ❌ NOT investment recommendation
- ✅ Educational tool for strategy monitoring
- ✅ Track your own strategy implementation

**Always DYOR (Do Your Own Research) before executing any crypto strategy.**

## 📞 Support

- Issues? Check [STRATEGY_GUIDE.md](docs/STRATEGY_GUIDE.md) FAQ
- Need updates? Fork & modify locally
- Questions? Review strategy documentation

## 📄 License

This project is open source for personal use and educational purposes.

---

**Last Updated:** May 19, 2026  
**Dashboard Status:** ✅ Live & Ready  
**Next Milestone:** 0.25 BTC target

**💡 Pro Tip:** Bookmark this page and visit monthly to track progress! 📈
