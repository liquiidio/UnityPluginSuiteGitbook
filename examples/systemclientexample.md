---
description: Example showing how to use the SystemClient
---

# SystemClientExample

```csharp
public async Task SystemClientExample()
{
    var systemClient = new SystemClient(new HttpHandler());

    // Request information about Proposals
    var proposals = await systemClient.GetProposalsAsync(proposer: "someproposer", cancellationToken: CancellationToken.None);

    // Write diverse Information about Proposals to the Console
    foreach (var proposal in proposals.Proposals)
    {
        Console.WriteLine(proposal.BlockNum);
        Console.WriteLine(proposal.Executed);
        Console.WriteLine(proposal.PrimaryKey);
        Console.WriteLine(proposal.ProposalName);
        Console.WriteLine(proposal.Proposer);

        // Write Information about Approvals to the Console
        foreach (var approval in proposal.ProvidedApprovals)
        {
            Console.WriteLine(approval.Actor);
            Console.WriteLine(approval.Permission);
            Console.WriteLine(approval.Time);
        }

        // Write information about requested Proposals to the Console
        foreach (var requestedApproval in proposal.RequestedApprovals)
        {
            Console.WriteLine(requestedApproval.Actor);
            Console.WriteLine(requestedApproval.Permission);
            Console.WriteLine(requestedApproval.Time);
        }
    }
}
```
