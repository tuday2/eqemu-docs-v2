=== "Perl (77)"

    !!! info end

        Also see [Spire Quest API Explorer](http://spire.akkadius.com/quest-api-explorer?lang=perl&type=Bot){:target="Bot"} for latest definitions and Quest examples

        Last generated 2023.06.12

    ``` perl
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges, bool attuned, uint32 aug1, uint32 aug2, uint32 aug3);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges, bool attuned);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges, bool attuned, uint32 aug1);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges, bool attuned, uint32 aug1, uint32 aug2);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges, bool attuned, uint32 aug1, uint32 aug2, uint32 aug3, uint32 aug4);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges, bool attuned, uint32 aug1, uint32 aug2, uint32 aug3, uint32 aug4, uint32 aug5);
    $bot->AddBotItem(uint16 slot_id, uint32 item_id, uint16 charges, bool attuned, uint32 aug1, uint32 aug2, uint32 aug3, uint32 aug4, uint32 aug5, uint32 aug6);
    $bot->AddItem(reference table_ref);
    $bot->ApplySpell(int spell_id);
    $bot->ApplySpell(int spell_id, int duration);
    $bot->ApplySpell(int spell_id, int duration, bool allow_pets);
    $bot->ApplySpellGroup(int spell_id, int duration);
    $bot->ApplySpellGroup(int spell_id, int duration, bool allow_pets);
    $bot->ApplySpellGroup(int spell_id);
    $bot->Camp(bool save_to_database);
    $bot->Camp();
    $bot->CountAugmentEquippedByID(uint32 item_id);
    $bot->CountBotItem(item_id);
    $bot->CountItemEquippedByID(uint32 item_id);
    $bot->Escape();
    $bot->Fling(float value, float target_x, float target_y, float target_z, bool ignore_los, bool clip_through_walls);
    $bot->Fling(float value, float target_x, float target_y, float target_z, bool ignore_los);
    $bot->Fling(float value, float target_x, float target_y, float target_z);
    $bot->Fling(float target_x, float target_y, float target_z, bool ignore_los, bool clip_through_walls);
    $bot->Fling(float target_x, float target_y, float target_z, bool ignore_los);
    $bot->Fling(float target_x, float target_y, float target_z);
    $bot->GetAugmentAt(int16 slot_id, uint8 augment_index);
    $bot->GetAugmentIDAt(int16 slot_id, uint8 aug_slot);
    $bot->GetAugmentIDsBySlotID(int16 slot_id);
    $bot->GetBaseAGI();
    $bot->GetBaseCHA();
    $bot->GetBaseDEX();
    $bot->GetBaseINT();
    $bot->GetBaseSTA();
    $bot->GetBaseSTR();
    $bot->GetBaseWIS();
    $bot->GetBotID();
    $bot->GetBotItem(uint16 slot_id);
    $bot->GetBotItemIDBySlot(uint16 slot_id);
    $bot->GetExpansionBitmask();
    $bot->GetGroup();
    $bot->GetHealAmount();
    $bot->GetInstrumentMod(uint16 spell_id);
    $bot->GetItemAt(int16 slot_id);
    $bot->GetItemIDAt(int16 slot_id);
    $bot->GetOwner();
    $bot->GetRawItemAC();
    $bot->GetSpellDamage();
    $bot->HasAugmentEquippedByID(uint32 item_id);
    $bot->HasBotItem(uint32 item_id);
    $bot->HasBotSpellEntry(uint16 spellid);
    $bot->HasItemEquippedByID(uint32 item_id);
    $bot->IsGrouped();
    $bot->IsSitting();
    $bot->IsStanding();
    $bot->OwnerMessage(string message);
    $bot->ReloadBotDataBuckets();
    $bot->ReloadBotOwnerDataBuckets();
    $bot->ReloadBotSpellSettings();
    $bot->ReloadBotSpells();
    $bot->RemoveBotItem(uint32 item_id);
    $bot->SendPayload(int payload_id, string payload_value);
    $bot->SendPayload(int payload_id);
    $bot->SendSpellAnim(uint16 target_id, uint16 spell_id);
    $bot->SetExpansionBitmask(int expansion_bitmask, bool save);
    $bot->SetExpansionBitmask(int expansion_bitmask);
    $bot->SetSpellDuration(int spell_id);
    $bot->SetSpellDuration(int spell_id, int duration);
    $bot->SetSpellDuration(int spell_id, int duration, bool allow_pets);
    $bot->SetSpellDurationGroup(int spell_id);
    $bot->SetSpellDurationGroup(int spell_id, int duration, bool allow_pets);
    $bot->SetSpellDurationGroup(int spell_id, int duration);
    $bot->Signal(int signal_id);
    $bot->Sit();
    $bot->Stand();
    ```
=== "Lua (85)"

    !!! info end

        Also see [Spire Quest API Explorer](http://spire.akkadius.com/quest-api-explorer?lang=lua&type=Bot){:target="Bot"} for latest definitions and Quest examples

        Last generated 2023.06.12

    ``` lua
    bot:AddBotItem(uint16 slot_id, uint32 item_id);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges, bool attuned);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges, bool attuned, uint32 augment_one);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges, bool attuned, uint32 augment_one, uint32 augment_two);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges, bool attuned, uint32 augment_one, uint32 augment_two, uint32 augment_three);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges, bool attuned, uint32 augment_one, uint32 augment_two, uint32 augment_three, uint32 augment_four);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges, bool attuned, uint32 augment_one, uint32 augment_two, uint32 augment_three, uint32 augment_four, uint32 augment_five);
    bot:AddBotItem(uint16 slot_id, uint32 item_id, int16 charges, bool attuned, uint32 augment_one, uint32 augment_two, uint32 augment_three, uint32 augment_four, uint32 augment_five, uint32 augment_six);
    bot:AddItem(const object& item_table);
    bot:ApplySpell(int spell_id);
    bot:ApplySpell(int spell_id, int duration);
    bot:ApplySpell(int spell_id, int duration, bool allow_pets);
    bot:ApplySpellGroup(int spell_id);
    bot:ApplySpellGroup(int spell_id, int duration, bool allow_pets);
    bot:ApplySpellGroup(int spell_id, int duration);
    bot:ApplySpellRaid(int spell_id, int duration, bool allow_pets);
    bot:ApplySpellRaid(int spell_id, int duration, bool allow_pets, bool is_raid_group_only);
    bot:ApplySpellRaid(int spell_id);
    bot:ApplySpellRaid(int spell_id, int duration);
    bot:Camp();
    bot:Camp(bool save_to_database);
    bot:CountAugmentEquippedByID(uint32 item_id);
    bot:CountBotItem(item_id);
    bot:CountItemEquippedByID(uint32 item_id);
    bot:Escape();
    bot:Fling(float target_x, float target_y, float target_z, bool ignore_los, bool clip_through_walls);
    bot:Fling(float value, float target_x, float target_y, float target_z);
    bot:Fling(float value, float target_x, float target_y, float target_z, bool ignore_los);
    bot:Fling(float value, float target_x, float target_y, float target_z, bool ignore_los, bool clip_through_walls);
    bot:Fling(float target_x, float target_y, float target_z, bool ignore_los);
    bot:Fling(float target_x, float target_y, float target_z);
    bot:GetAugmentAt(int16 slot_id, uint8 augment_index);
    bot:GetAugmentIDAt(int16 slot_id, uint8 augment_index);
    bot:GetAugmentIDsBySlotID(int16 slot_id);
    bot:GetBaseAGI();
    bot:GetBaseCHA();
    bot:GetBaseDEX();
    bot:GetBaseINT();
    bot:GetBaseSTA();
    bot:GetBaseSTR();
    bot:GetBaseWIS();
    bot:GetBotID();
    bot:GetBotItem(uint16 slot_id);
    bot:GetBotItemIDBySlot(uint16 slot_id);
    bot:GetExpansionBitmask();
    bot:GetGroup();
    bot:GetHealAmount();
    bot:GetInstrumentMod(spell_id);
    bot:GetItemAt(int16 slot_id // @categories Inventory and Items);
    bot:GetItemIDAt(int16 slot_id);
    bot:GetOwner();
    bot:GetRawItemAC();
    bot:GetSpellDamage();
    bot:HasAugmentEquippedByID(uint32 item_id);
    bot:HasBotItem(uint32 item_id);
    bot:HasBotSpellEntry(uint16 spellid);
    bot:HasItemEquippedByID(uint32 item_id);
    bot:IsGrouped();
    bot:IsSitting();
    bot:IsStanding();
    bot:OwnerMessage(string message);
    bot:ReloadBotDataBuckets();
    bot:ReloadBotOwnerDataBuckets();
    bot:ReloadBotSpellSettings();
    bot:ReloadBotSpells();
    bot:RemoveBotItem(uint32 item_id);
    bot:SendPayload(int payload_id);
    bot:SendPayload(int payload_id, string payload_value);
    bot:SendSpellAnim(uint16 target_id, uint16 spell_id);
    bot:SetExpansionBitmask(int expansion_bitmask);
    bot:SetExpansionBitmask(int expansion_bitmask, bool save);
    bot:SetSpellDuration(int spell_id);
    bot:SetSpellDuration(int spell_id, int duration, bool allow_pets);
    bot:SetSpellDuration(int spell_id, int duration);
    bot:SetSpellDurationGroup(int spell_id, int duration);
    bot:SetSpellDurationGroup(int spell_id);
    bot:SetSpellDurationGroup(int spell_id, int duration, bool allow_pets);
    bot:SetSpellDurationRaid(int spell_id, int duration, bool allow_pets, bool is_raid_group_only);
    bot:SetSpellDurationRaid(int spell_id);
    bot:SetSpellDurationRaid(int spell_id, int duration);
    bot:SetSpellDurationRaid(int spell_id, int duration, bool allow_pets);
    bot:Signal(int signal_id);
    bot:Sit();
    bot:Stand();
    ```
