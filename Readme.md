# Crypto Swipe API GateWay
### Functional for v0.1
> #### Auth Service:
> > ##### /auth/sign-up
> > ##### /auth/sign-in
> ______
> #### Report Service:
> >##### For reporting: /:user_id/report
> >##### For admins: /admin/reports
> _____
> #### Interests Service:
> > ##### Join to Community: /interests/join/{id} 
> > ##### Leave From Community: /interests/leave/{id} (and info in request-body)
> > ##### Get Members by InterestID: /interests/members/{id}
> > ##### Get Interests by UserID: /interests/user/{user_id}
> > ##### For Admin: Statistic of Interests
> _____
> #### Swipe Service:
> > ##### Get Random: /swipe/
> > ##### Accept: /swipe/accept/{user_id}
> > ##### Accept: /swipe/deny/{user_id}
> ______
> #### Wallet Service:
> > ##### Get Wallets: /wallets/get/{user_id}
> > ##### Add Wallet: /wallets/add/{user_id}
> > ##### Remove Wallet: /wallets/remove/{user_id}
> > ##### Transfer: /wallets/transfer/{user_id}
> _______
> #### NFT Service:
> > ##### Buy NFT: /marketplace/buy/{nft_id}
> > ##### Sell NFT: /marketplace/sell/{nft_id}
> > ##### Get Available NFT: /marketplace/
> ______
> #### Chat Service:
> > ##### Create chat with User: /messenger/{user_ud}
> > ##### Delete chat with User: /messenger/{user_ud}
> > ##### Get Chats: /messenger/
> > ##### Get Chat: /messenger/{chat_id}
> > ##### Update Message: /messenger/{chat_id}/message/{message_id}
> > ##### Delete Message: /messenger/{chat_id}/message/{message_id}
